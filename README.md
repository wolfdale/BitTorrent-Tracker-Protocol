BitTorrent-Tracker-Protocol
===========================
Status : Incomplete(sort-of)<br/>
Getting torrent info from tracker (UDP) 
<p>
To discover other peers in a swarm a client sends a <b>UDP</b> packet announcing its existence to the tracker. The request and response are quite short. if <b>TCP</b> is used, a connection has to be opened and closed, introducing additional overhead. Therefore UDP, a connectionless protocol is used to avoid such overheads. </p>
