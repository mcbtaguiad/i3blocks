# i3blocks


[network_status.sh]
command=~/.config/i3blocks/scripts/network_status.sh 
interval=once
signal=1

Add to NetworkManager dispatcher.d (/etc/NetworkManager/dispatcher.d). 
pkill -SIGRTMIN+1 i3blocks
