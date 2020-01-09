Ubuntu Server Student Environment
=================================

Scripts and config files for configuring an Ubuntu server for multiuser student use

Installation
------------

After a clean installation of Ubuntu Server, a new system can be configured by running as a sudoer:

`curl https://raw.githubusercontent.com/jncraton/ubuntu-server-student-env/master/setup | bash`

For a complete list of packages and tools that are available, view the `setup` script.

Adding Students
---------------

After successful installation, students can be added using the following command:

`addstudent alice bob charlie`

This will create new users and home directories for each student. Accounts will be given a default password of Password1.
