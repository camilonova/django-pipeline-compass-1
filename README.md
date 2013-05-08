# Django Pipeline Compass

[Compass](http://compass-style.org/) compiler for django-pipeline using the original Ruby gem.

## Requirements

- Compass: `gem install compass`

## Installation

```
pip install git+https://github.com/mila-labs/django-pipeline-compass.git
```

## Usage

```python
# settings.py

PIPELINE_COMPASS_BINARY = '/usr/local/bin/compass'   # default: '/usr/bin/env compass'
PIPELINE_COMPASS_PROJECT_PATH = '/absolute/path/to/project/'    # default: ''
PIPELINE_COMPASS_ARGUMENTS = '-c /absolute/path/to/project/config.rb'  # default: ''

PIPELINE_COMPILERS = (
  'pipeline_compass.compass.CompassCompiler',
)
```

