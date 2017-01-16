# tower-example-extra-module-without-library

To run it successfully in tower, should do the following the steps:

* Download the extra module to /usr/share/my_modules/ansible-modules-extras/
  ```
  git clone https://github.com/ansible/ansible-modules-extras.git
  
  ```
  
* Umcomment the line and modfy as below in /etc/ansible/ansible.cfg

  ```
  library        = /usr/share/my_modules/ansible-modules-extras
  ```
