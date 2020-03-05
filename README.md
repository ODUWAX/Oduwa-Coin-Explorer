# Oduwa-Coin-Explorer  & Seed Server
API Documentation The block explorer provides an API allowing users and/or applications to retrieve information from the network without the need for a local wallet.
(http://oduwaexplorer.com/)<br>




1 - Stop your wallet.
2 - search run on start menu and open this. %appdata%\OduwaCoin\
3 - open OduwaCoin.conf file on notepad and add this lines.
addnode=134.209.13.43
addnode=142.93.143.35
addnode=68.183.115.49
addnode=167.172.121.86
addnode=157.230.29.96
4 - Start your wallet again. you will get automatic connection in your wallet




Adding nodes using configuration file
Using the above console method you’ll have to manually add nodes one by one but what if you want to add a huge list of nodes to your wallet. This can be done by adding the complete node list to your wallet’s config file.

First you’ll need to find your wallet directory. In Windows it can be found at C:\Users\YOUR-USERNAME\Appdata\Roaming\OduwaCoin.
In Linux it should be at /home/USER/.OduwaCoin-DIR.
Inside your wallet folder you should see several files such as blocks, peers.dat, wallet.dat, .conf etc. Nodes should be added in the .conf file.
In some wallets you may not find this .conf file and in such case you’ll have to create one. To create a .conf file all you have to do is copy the wallet folder name, create a text document and save it as OduwaCoin.conf
Now open the .conf file in notepad or notepad ++ and paste all the node lists.
Once done, save the .conf file and re open your wallet.
That’s it! Your wallet should now connect to the network and start synchronizing. If you have further question contact 
info@Oduwacoin.io

Thank You
Oduwa Dev Team 
"Empower Yourself"
