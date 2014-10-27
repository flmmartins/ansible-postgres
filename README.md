ansible-postgres
========

Install and configure postgres

Role Variables
--------------

In defaults:

db_user - Name of a user to be able to create databases
db_password - Password from this user

Generate password with the command bellow and paste the blob in the variable

python -c "from passlib.hash import sha512_crypt; import getpass; print sha512_crypt.encrypt(getpass.getpass())"


Author Information
------------------

Fernanda Martins (flmmartins@gmail.com)
LinkedIn: https://www.linkedin.com/in/flmmartins
