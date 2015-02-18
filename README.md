ansible-redmine-example
=====================

This project contains an example usage of the [ansible-redmine](https://github.com/hicknhack-software/ansible-redmine) roles.

Requirements
------------

* Vagrant with VirtualBox
* A shell that can run Windows 7 batch files or Bash shell scripts
* A working internet connection

Basic Usage
-----------

1. Clone this repository
   ```bash
   git clone https://github.com/hicknhack-software/ansible-redmine-example --recurse-submodules
   ```
1. Create an SSH identity RSA key pair
   1. Copy the public key to `ansible/id_rsa.pub`
   1. Add the created key and the vagrant keys to your ssh_agent
   1. For Windows you might want to use [ssh-pageant](https://github.com/cuviper/ssh-pageant)
1. Run the `remote.bat` or `remote.sh` *this might take a while*
1. Open http://127.0.0.1:8081 in your browser

Advanced Usage
--------------

These examples are meant as starting points for your own projects.
Feel free to combine your roles with ours.

**Please consider open sourcing generic roles or ideas**

License
-------

The MIT License (MIT)

Copyright (c) 2014 HicknHack Software GmbH

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
