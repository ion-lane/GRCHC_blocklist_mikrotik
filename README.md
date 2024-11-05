Source: https://raw.githubusercontent.com/C24Be/AS_Network_List/main/blacklists/blacklist.txt

/tool/fetch address=raw.githubusercontent.com host=raw.githubusercontent.com mode=https src-path=ion-lane/GRCHC_blocklist_mikrotik/main/grchc.src

/ip/firewall/address-list/remove [find where list="GRCHC"]

/import grchc.src
