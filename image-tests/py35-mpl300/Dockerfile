# This docker image is intended to be used for packages that need to do
# image tests with e.g. pytest-mpl and guarantees fixed versions of other
# libraries such as freetype.

FROM astropy/image-tests-py35-base:1.0

RUN pip3 install setuptools pip --upgrade
RUN pip3 install pytest pytest-mpl pytest-astropy numpy==1.15.1 matplotlib==3.0.0 scipy==1.1.0
