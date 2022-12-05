#Enhanced ICMP Backdoor

#Usage

# On server
sudo python3 icmp_cnc.py -i eth0

# On client
sudo python3 icmp_client.py -i eth0 -d 10.10.10.10

Tested on Kali Linux but should be compatible with almost everything.

Thanks to krabelize for the idea.
The code is "as-is", anything you do with it is your responsibility. Use it only in authorized enviroments. I take no credit for whatever illegal shit you do with it. Love ♥
