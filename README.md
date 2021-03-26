# Tensorflow release
VXST's build of Tensorflow release for Python 3.9 on ARM64 and AMD64.

Warning! Python 3.9 is not supported by Tensorflow officially. Some calls may fail. The use case of these packages is to provide a developing environment(E.g. Jedi support) for those who use python 3.9 as the python interpreter.

However, it seems ok to use these packages in a development environment where only auto-completion and lint are needed. Tested under vxst-workspace docker image, and it works.
