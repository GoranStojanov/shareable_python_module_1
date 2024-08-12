# SHARED_PACKAGE

This project provides a sample shared module: shared_util with one sample class SharedClass. All classes in this module can be used in multiple projects as a shared module. 

## Table of Contents

* [Build](#build)
* [Use](#use) 
* [Install](#install)

### Build

To build this module run in the root of the project:

python setup.py sdist

This will create a folder dist and inside of it a file: shared_util-1.0.0.tar.gz

### Use
To use it in a project add:
from shared_util.shared_class import SharedClass

### Install
To install it in a project run:
pip install ../shared_package/dist/shared_util-1.0.0.tar.gz                              