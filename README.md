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
context=telepon
secret=001
username=client1
host=dynamic
disallow=all
allow=ulaw
allow=alaw
allow=h263p
allow=h264
allow=pv8
videosupport=yes






