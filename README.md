# cpp_class_generator
A python prog to authomatically create c++ class

It use the [Cheetah template engine](http://www.cheetahtemplate.org/index.html).


## Installing on Mac OSX
First you have to download cheetah :
https://pypi.python.org/pypi/Cheetah/2.4.4

To install cheetah without the root rights, de-tar it, go inside the folder and run the following command :
python setup.py install --user

## Execution
Just use the python command on main.py. If your program is in the ~/progs folder, adding the following alias to your [.zshrc, bashrc] will do it :
alias class="python ~/progs/cpp_class_generator/main.py"