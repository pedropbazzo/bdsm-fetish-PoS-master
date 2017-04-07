

<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />

</head>
<body><div class="container"><h1 id="bdsm-fetish">BDSM-FETISH </h1>

<p><div class="toc">
<ul>
<li><a href="#bdsm-fetish">BDSM-FETISH Fully PoS </a><ul>
<li><a href="#1-specs">1. Specs</a></li>
<li><a href="#2-blockexplorer">2. Blockexplorer</a></li>
<li><a href="#2a-blockexplorer">2.1 Blockexplorer and closing my connected nodes</a></li>
<li><a href="#3-coin-count">3. Coin Count</a></li>
<li><a href="#4-connections">4. Connections</a></li>
<li><a href="#5-trade">5. Trade</a></li>
<li><a href="#6-news">6. News</a></li>
<li><a href="#7-wallets">7. Wallets</a></li>
<li><a href="#8-compiling-daemon-bdsm-fetishd">8. Compiling Daemon: BDSM-FETISHd</a></li>
<li><a href="#9-sample-minimal-server-conf">9. Sample Minimal Server .conf</a></li>
<li><a href="#10-Compiling Iquidus Explorer">10. Compiling Iquidus Explorer</a></li>
</ul>
</li>
</ul>
</div>


<hr>

<p><img src="https://cdn.pbrd.co/images/MxL0DyaUg.png" alt="WHIPPED" title=""></p>

<h2 id="1-specs">1. Specs</h2>

<blockquote>
  <p>Coin: BDSM-FETISH FULLY PoS (X11 Algo)</p>
  
  <p>Ticker: WHIPPED</p>
  
  <p>rpc port: 8746</p>
  
  <p>p2p port: 8745</p>
  
  <p>About 200 blocks are mined via staking every 24 hours.</p>
  
  <p>2 percent interest a year.</p>
</blockquote>

<hr>

<h2 id="2-blockexplorer">2. Blockexplorer</h2>

<p><a href="http://explorer.bdsm-fetish.net:3001">Explorer</a></p>

<p>See below: The above link will not be live from now on.</p>

<hr>

<h2 id="2a-blockexplorer">2.1 Blockexplorer and closing my connected nodes</h2>

The Explorer will be switched off, as there is no interest other than from a couple of parties. So they can pay.

<hr>

<h2 id="3-coin-count">3. Coin Count</h2>

<p>Of 850,000 stated available coins on the Explorer, 300,000 were destroyed: 20,000 accidently deleted by me and 100,000 remain somewhere at Cryptopia. probably spent.</p>

<p><a href="http://explorer.bdsm-fetish.net:3001/richlist">Explorer Rich List</a></p>

<p><strong>That results in about 430,000 WHIPPED available, nearly half of the coin count.</strong></p>

<p>See above: The link will not be live from now on.</p>

<blockquote>
  <p>Burn Address:</p>
  
  <p><a href="http://explorer.bdsm-fetish.net:3001/address/BFTheseCoinsAreDestroyedXXXXZ9jn9o">BFTheseCoinsAreDestroyedXXXXZ9jn9o</a></p>
</blockquote>

<p>See above: The link will not be live from now on.</p>

<hr>

<h2 id="4-connections">4. Connections</h2>

<p>For Nodes (check the Explorer “network”): <a href="http://explorer.bdsm-fetish.net:3001/network">Explorer Network</a></p>

<p>See above: The link will not be live from now on.</p>

<hr>

<h2 id="5-trade">5. Trade</h2>

<p>Trade at Nova Exchange: <a href="https://novaexchange.com/market/BTC_WHIPD/">Nova Exchange</a></p>

<blockquote>
  <p>Current Price: Sell at 1000 Sats; Buy at 15 Sats</p>
</blockquote>

<hr>

<h2 id="6-news">6. News</h2>

<p>Cryptopia Exchange kicked us off by pretending I had requested to be removed. I had said it was okay to remove WHIPPED if they desired, after publicly criticizing the Cryptopia management double act of a naive “tactical” quest to be a leading exchange. I even went as far as suggesting it was not a good idea to call customers “wankers” or say “fuck off, we hate you”. Nor is it clever to comment to people for not buying their Cryptopia shares.</p>

<p>I specifically did not say I desire they remove BDSM-FETISH. Verbal and personal abuse followed from management when I pointed that fact out.</p>

<p>I always suspected Cryptopia was selling behind peopleś backs, and staking coins. Bizarrely, it is still attached to the network.</p>

<hr>

<p><img src="https://cdn.pbrd.co/images/1f441jdI6.png" alt="WHIPPED" title="Cryptopia IP Block"></p>
<br>
<br>
<p><img src="https://cdn.pbrd.co/images/1f7LojOkd.png" alt="WHIPPED" title="Cryptopia Staking Why?"></p>
<br>
<br>
<p><img src="https://cdn.pbrd.co/images/4MzkS9j.png" alt="WHIPPED" title="Stolen Lost Bought Whatever Cryptopia"></p>

<hr>

<h2 id="7-wallets">7. Wallets</h2>

<p>See website or here on <a href="https://github.com/bdsmc/Windows-Mac-OSX-Wallets">Github</a>.</p>

<p>Available in Windows, Mac OSX and Linux</p>

<hr>

<h2 id="8-compiling-daemon-bdsm-fetishd">8. Compiling Daemon: BDSM-FETISHd</h2>

<p>There are various methods, the most simple is using Ubuntu 14x or Debian 7x 64 bit.</p>

<blockquote>
  <p><em>Dependencies (if you need to start from the beginning):</em></p>
  
  <p>$ sudo apt-get install git build-essential libssl-dev libboost-all-dev libqrencode-dev libdb++-dev libminiupnpc-dev qt-sdk -y</p>
</blockquote>

<p>cd into dir/src</p>

<blockquote>
  <p>$  make -f makefile.unix</p>
  
  <p>$  strip BDSM-FETISHd</p>
  
  <p>$  ./BDSM-FETISHd</p>
</blockquote>

<hr>



<h2 id="9-sample-minimal-server-conf">9. Sample Minimal Server type .conf</h2>

<blockquote>
  <p>$  nano /root/.BDSM-FETISH/BDSM-FETISH.conf</p>
</blockquote>

<p>BDSM-FETISH.conf</p>

<blockquote>
  <p>daemon=1</p>
  
  <p>rpcuser=BDSM-FETISHrpc</p>
  
  <p>rpcpass=whateveryouaregivnwhensstartingtheserver</p>
  
  <p>rpcallowip=127.0.0.1</p>
  
  <p>rpcport=8746</p>
</blockquote>

<p><em>You can “addnode=” if you want to, and place the p2p port in the conf file. Some people like to add “server=1” and “listen=1”.</em></p>

<hr>

<h2 id="10-Compiling Iquidus Explorer">10. Compiling Iquidus Explorer</h2>

<p>I will put instructions up for compiling a simple Blockexplorer, and the right BDSM-FETISH settings, should anyone desire to use them</p>

</div></body>
</html>
