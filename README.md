# Nmap-DNS-Update
Modifed NSE script to update DNS entries (does not delete)

`nmap -sU -p 53 10.0.0.1 --script ./dns-update.nse --script-args=dns-update.hostname=wpad.contoso.com,dns-update.ip=10.0.0.2`
