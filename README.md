---


---

<h1 id="easykatana">EASYKATANA</h1>
<p>Easy daemon setup for katana2x masternode for fresh VPS installation<br>
this tool is very simple that can handle library for katana coin daemon, compile the daemon and prepare data directory each k2xmn<br>
and create file <a href="http://runmn.sh">runmn.sh</a></p>
<h2 id="todo">TODO</h2>
<ul>
<li>open file <a href="http://easykatana.sh">easykatana.sh</a>, change max=NUMBER_YOUR_MN</li>
<li>UPLOAD <a href="http://easykatana.sh">easykatana.sh</a> and <a href="http://setswapfile.sh">setswapfile.sh</a> to your VPS using winscp on your $HOME directory</li>
<li>run setswapfile: <code>sh ./setswapfile.sh</code></li>
<li>Begin katana daemon installation: <code>sh ./easykatana.sh</code></li>
<li>open katana.conf on your vps (default ~/.katana2x1; ~/.katana2x2; ~/.katana2xmax) paste your generated genkey to masternodeprivkey=YOUR_GENKEY</li>
<li>call <a href="http://runmn.sh">runmn.sh</a>: <code>sh ./runmn.sh</code></li>
<li>Enjoy</li>
</ul>
<p><strong>tested on ubuntu server 16.04 on virtual box</strong><br>
<strong>please make sure each daemon have different masternodeprivkey copied from your local masternode.conf</strong><br>
<strong>always open your local wallet, this is a must to run cold wallet masternode.</strong><br>
HAPPY MASTERNODING!!</p>

