<<<<<<< HEAD
Browsermob-proxy
=========

Very tiny role to set up browsermob in standalone mode. 


Role Variables
--------------

`brwosermob_proxy_url`   
Normally you don't need to change it. Default value is `"https://github.com/lightbody/browsermob-proxy/releases/download/browsermob-proxy-{{ browsermob_proxy_version }}/browsermob-proxy-{{ browsermob_proxy_version }}-bin.zip"`.

`browsermob_proxy_version`
Default to 2.1.4.

`browsermob_user`
A user to create(if needed) root directory/extract archive. Defaults to root. 

`browsermob_proxy_dest`
Where package with browsermob will be extracted. Defaults to `/opt/`. Note that browsermob allows
you to configure user to check root directory and extract archive. 
 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: andreyrusanov.browsermob-proxy }

License
-------

MIT

Author Information
------------------

The role is extremely easy. Contributors are welcome.
=======
# browsermob-proxy
>>>>>>> 5893bef5ec3b99ea89b3f1548dc9dfa78690f182
