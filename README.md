# ceda-theme-django

Django app providing Django base templates for CEDA websites.

The static files from the [CEDA theme package](https://github.com/cedadev/ceda-theme)
are included as a [Git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules),
for local development, but production installs should use a static content server.

## Installation

`ceda-theme-django` can be installed directly from Github using pip:

```
$ pip install git+https://github.com/cedadev/ceda-theme-django.git
```

## Developing

When developing `ceda-theme-django`, you must ensure that you include the
`--recursive` flag when cloning to ensure that the `ceda-theme` submodule is
properly initialised:

```
$ git clone --recursive git@github.com:cedadev/ceda-theme-django.git
```
