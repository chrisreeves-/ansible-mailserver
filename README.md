# ansible-mailserver

<h2> Full Decription: </h2>

The full description of the script can be found at https://chrisreeves.co.nz

<h2> Scope </h2>

This script installs and configures the following packages and services:

* Apache
* PHP 7.2
* MySQL
* Postfix
* Dovecot
* Sieve
* SpamAssassin
* Postgrey
* iptables
* Roundcube Webmail

<h2> Dependancies: </h2>

Ansible Roles: geerlingguy.firewall & thefinn93.letsencrypt

<pre>
ansible-galaxy install geerlingguy.firewall
</pre>

<pre>
ansible-galaxy install thefinn93.letsencrypt
</pre>
