# easykatana
Easy daemon setup for katana2x masternode for fresh VPS installation
this tool is very simple that can handle library for katana coin daemon, compile the daemon and prepare data directory each k2xmn
and create file runmn.sh

##TODO
open file easykatana.sh 
change max=NUMBER_YOUR_MN
eg: max=4 for 4 MN setup
UPLOAD easykatana.sh and setswapfile.sh to your VPS using winscp on your $HOME directory
If you are using 1GB RAM VPS, run setswapfile:
sh ./setswapfile.sh
wait until finished.
Begin katana daemon installation:
sh ./easykatana.sh
command above will prepare your katana daemon library, clone katana source, and compile your source
After finished all step above, open katana.conf on your vps (default ~/.katana2x1; ~/.katana2x2; ~/.katana2xmax)
paste your generated genkey to masternodeprivkey=YOUR_GENKEY
now, call runmn.sh
sh ./runmn.sh
your katana daemon run

*tested on ubuntu server 16.04 on virtual box
*please make sure each daemon have different masternodeprivkey copied from your local masternode.conf
*always open your local wallet, this is a must to run cold wallet masternode.
HAPPY MASTERNODING!!
