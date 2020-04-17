# deluge-compose
deluged + deluge web ui docker-compose

based on linuxserver/docker-deluge
and all credit should go to them


Guide


Clone or Download repo

open docker-compose.yml in a text editor
locate 

volumes:
	- PATH-TO-REPO/deluge-compose/deluge-config/:/config
	- PATH-TO-DOWNLOADS-FOLDER/:/downloads

and change the PATH-TO

example:
	- /home/{username}/deluge-compose/deluge-config/:/config
	- /home/{username}/Downloads/:/downloads

Save and Exit


$ cd deluge-compose

$ docker-compose up

open host-ip-adress:8112 in your browser

default password: deluge
you can change it from the prompt or in Preferences/Interface

Connect to you deluged server with user localclient
-> Open Connection Manager
	There should be a default localclient@127.0.0.1:58846
-> Press Connect






