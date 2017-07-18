## rpi-opensprinkler  
=========

This role is designed to install OpenSprinkler on the Raspberry Pi  

Requirements  
------------

None.  

Role Variables
--------------

None needed

Dependencies
------------

None

Example Playbook
----------------

- name: Setup OpenSprinkler on the Raspberry Pi
  hosts: all  
  remote_user: pi  

  roles:  
    - role: rpi-opensprinkler  

License
-------

BSD

Author Information
------------------

My goal is to make this as easy as possible and to run over an over again with no headaches.  Feel free to make an issue if something pops up.  Hopefully travis-ci will catch anything in time of you trying this outMy goal is to make this as easy as possible and to run over an over again with no headaches.  In my testing, I used this on a pi0 and pi3.
