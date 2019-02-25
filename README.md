# ansible-mailserver

<h2> Full Description: </h2>

The full description of the script can be found at https://chrisreeves.co.nz

<h2> Scope: </h2>

This script installs and configures the following packages and services:

* Apache
* PHP 7.2
* MySQL
* Postfix
* Dovecot
* Letsencrypt
* Sieve
* SpamAssassin
* Postgrey
* iptables
* Roundcube Webmail
  ** managesieve plugin
  ** two_factor_auth plugin

<h2> Requirements: </h2>

1. Ansible control server
2. SSH keys established between Ansible control server and destination server(s)
3. 2x Public DNS A records pointing to the server to be set up

<h2> Dependancies: </h2>

Ansible Roles: geerlingguy.firewall & thefinn93.letsencrypt

<pre>
ansible-galaxy install geerlingguy.firewall
</pre>

<pre>
ansible-galaxy install thefinn93.letsencrypt
</pre>
