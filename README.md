# ansible-linode-DNS-updater
The following playbooks goes out and check what your current IP is and then updates the DNS record dynamicly every hour. This role also sets up a cron job to run every hour. This is my drop in replacement for NO-IP or any dynamic hosting

You will need to edit the following roles: linode-dns-updater with the the domain's ID and the records ID AND linode-dns-updater-cron with the path to the ansible playbooks. 

Detailed instructions can be found @ https://www.milehighhacking.com/2021/02/14/setting-up-dynamic-dns-updates-with-ansible-and-linode/
