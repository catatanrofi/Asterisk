# Asterisk
Cara menginstal Asterisk di Linux Debian

<h3>INSTALASI</h3>
<p>$ apt-get update -y</p>
<p>$ apt-get upgrade -y</p>
<p>$ apt-get install asterisk</p>
<h3>Konfigurasi SIP</h3>
<p>$ nano /etc/asterisk/sip.conf</p><br>
<p><b>KEBAGIAN BARIS PALING BAWAH KEMUDIAN, TAMBAHKAN PERINTAH DIBAWAH INI.</b></p>
<p>[001]</p>
<p>type=friend</p>





