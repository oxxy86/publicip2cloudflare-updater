# publicip2cloudflare-updater
This will update your cloudflare ip if you have a DHCP ip from your ISP






CRON
                                                 */5 * * * * /usr/bin/ansible-playbook -i /opt/ansible/inventory.ini /o*t/ansible/cloudflare-ddns.yml >/de*/null 2>&1
