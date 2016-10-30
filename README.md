# QuickPackage
Instantly create and upload python package for your awesome script without reading any `Docs`

Just enter the path of your awsome python script and instantly package your script and upload it to [Pypi](https://pypi.python.org) . This would enable users to quickly install and use your script.
Also :
[Save time](http://stackoverflow.com/questions/15587877/run-a-python-script-in-terminal-without-the-python-command)

## Installation 
``` zsh
$ pip install quickpackage
```

##Usage

Simply run `quickpackage` from your terminal and enter the path of your python script.

Example:
``` zsh
❯ quickpackage                                                    
Enter name: quickpackage
Enter version: 1.1
Enter description: Instantly create and upload python package for your script
Enter github url: https://github.com/yask123/quick-package
enter author: Yask Srivastava
Enter email: yask123@gmail.com
Path of python script file: run.py
running register
....
running upload
Submitting dist/quickpackage-1.1.tar.gz to https://pypi.python.org/pypi
Server response (200): OK
```
