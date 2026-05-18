---
tags:
  - Python
  - Matplotlib
  - Functional
  - Machine Learning
---

<div style="display: flex;">


<div>
My opinionated library of custom Python scripts and configurations. `iragca` is a comprehensive Python library providing practical utilities for data science, machine learning, and visualization workflows. It streamlines common tasks in machine learning, data visualization, and functional programming.
</div>
</div>

[PyPi :material-web:](https://pypi.org/project/iragca/){ .md-button }
[GitHub :simple-github:](https://github.com/iragca/iragca-python){ .md-button }

## Key Features

- **Accessible Visualization**: Professional matplotlib styles and WCAG-compliant color palettes designed for clarity and accessibility.
- **Lightweight Experiment Tracking**: `RunLogger` for logging metrics with dynamic property access and optional progress bars.
- **Functional Programming Utilities**: Composable data transformation pipelines using `Pipeline` and `Step`.
- **Deprecation Management**: Tools to manage deprecations and guide users to alternatives.

## Use Cases

- **ML/DL Training**: Track metrics with `RunLogger` during training loops
- **Data Pipelines**: Build readable transformation chains with `Pipeline`
- **Publication Plots**: Create accessible visualizations with pre-configured styles
- **Library Maintenance**: Manage deprecations gracefully with proper warnings


## Example Usage

### RunLogger

```python
from iragca.ml import RunLogger

logger = RunLogger(max_steps=100, display_progress=True)
for epoch in range(100):
	loss = 1.0 / (epoch + 1)
	logger.log_metrics({'loss': loss}, step=epoch)

print(f"Final loss: {logger.loss[-1]}")
```

### Matplotlib Colors and Styles

```python
import matplotlib.pyplot as plt

from iragca.matplotlib import Color, Styles

plt.style.use(Styles.CMR10.value)

sample_data = [1, 3, 2, 4, 3, 5]

plt.plot(sample_data, color=Color.BLUE.value)
plt.title("Sample Plot with Custom Style and Color")
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.show()
```

<img src="../../../assets/sample_plot.png" width=300>

### Functional Pipelines

```python
from iragca.functional import Pipeline, Step

pipeline = Pipeline([
	lambda x: x * 2,
	Step(lambda x, n: x + n, n=10),
	lambda x: x ** 2,
])

result = pipeline(5)  # (5 * 2 + 10)^2 = 400
```