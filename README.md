# Asterisk
Cara menginstal Asterisk di Linux Debian

<h3>INSTALASI</h3>
<p>$ apt-get update -y</p>
<p>$ apt-get upgrade -y</p>
<p>$ apt-get install asterisk</p>
<h3>Konfigurasi SIP</h3>
<p>$ nano /etc/asterisk/sip.conf</p><br>
<p><b>KEBAGIAN BARIS PALING BAWAH KEMUDIAN, TAMBAHKAN PERINTAH DIBAWAH INI.</b></p>
<p>[general]</p>
<p>context=default</p>
<p>allowoverlap=no</p>
<p>bindaddr=0.0.0.0</p>
<p>srvlookup=yes</p>
<p>videosupport=yes</p>
<p>[001]</p>
<p>type=friend</p>
<p>context=telepon</p>
<p>secret=001</p>
<p>username=client1</p>
<p>host=dynamic</p>
<p>disallow=all</p>
<p>allow=ulaw</p>
<p>allow=alaw</p>
<p>allow=h263p</p>
<p>allow=h264</p>
<p>allow=pv8</p>
<p>videosupport=yes</p>






