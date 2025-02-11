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
## Development guide

If you intend to develop `base-components-drf` locally and want to test it in other base projects,   
it is advised you make your intended changes in `base-components-drf`.   
Then uninstall it from the other base project (ex. image, portofolio, showroom) you utilize it in.   
Lastly, install the newest version of your changes with uv pip in the following way:  
  
`uv pip uninstall base-common-drf`      
`uv pip install -e /local/path/of/your/base-common-drf` (with "-e" you command pip to not install the `base-common-drf` from PyPi, but your local version)  
  
This way you can successfully test your created feature, before the future release of `base-common-drf`.
