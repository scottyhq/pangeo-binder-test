# pangeo-binder-test
a place to test nasa binder examples with the latest python packages

NOTE: you might think that specifying `FROM pangeo/base-notebook:latest` in the Dockerfile:
https://github.com/scottyhq/pangeo-binder-test/blob/pangeo-base/binder/Dockerfile

will always pull the latest image. BUT! The build is linked to a git commit, so you must make a change to something (add a datestamp to this readme?) to re-trigger a pull.

[![badge](https://img.shields.io/static/v1.svg?logo=Jupyter&label=Pangeo+Binder&message=GCE+us-central1&color=blue)](https://binder.pangeo.io/v2/gh/scottyhq/pangeo-binder-test/pangeo-base?urlpath=lab)

[![badge](https://img.shields.io/static/v1.svg?logo=Jupyter&label=Pangeo+Binder&message=AWS+us-west-2&color=orange)](https://aws-uswest2-binder.pangeo.io/v2/gh/scottyhq/pangeo-binder-test/pangeo-base?urlpath=lab)
