/tool/fetch address=raw.githubusercontent.com host=raw.githubusercontent.com mode=https src-path=ion-lane/GRCHC_blocklist_mikrotik/main/bl_grchc.src

/ip/firewall/address-list/remove [find where list="GRCHC"]

/import bl_grchc.src
