# base-common-drf

base-common-drf is a Django app with common implementations for base Angewandte projects using Django REST Framework.

## Quick start

1. Install the package:

```
pip install base-common-drf
```

2. Add `base_common_drf` to your `INSTALLED_APPS` setting like this:

```
INSTALLED_APPS = [
    …,
    'base_common_drf',
]
```
## How to contribute

Follow [GitHub's Contribution Guide](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project) 
on how to create a pull request.

Before submitting a pull request, ensure that it is in line with our [Development Conventions](https://base-angewandte-docs.readthedocs.io/en/latest/dev_guide.html)
and that you have tested the changes in a Django project. For that you can follow the Quick Start Guide,
but instead of a normal pip install, install your local fork: `pip install -e /local/path/to/base-common-drf`
