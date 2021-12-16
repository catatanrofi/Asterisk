# Asterisk
Cara menginstal Asterisk di Linux Debian

<h3>INSTALASI</h3>
<p>$ apt-get update -y</p>
<p>$ apt-get upgrade -y</p>
<p>$ apt-get install asterisk</p>
<h3>Konfigurasi SIP</h3>
<p>$ nano /etc/asterisk/sip.conf</p>
<p>Kebagian Baris Paling Bawah Kemudian, Tambahkan Perintah yang ada di link berikut.</p>
<p>https://github.com/catatanrofi/Asterisk/blob/main/Konfigurasi%20SIP</p>
<h3>Konfigurasi extension</h3>
<p>$ nano /etc/asterisk/extensions.conf</p>
<p>Kebagian Baris Paling Bawah Kemudian, Tambahkan Perintah yang ada di link berikut.</p>
<p>https://github.com/catatanrofi/Asterisk/blob/main/Konfigurasi%20extension</p>
<h3>Restart Asterisk</h3>
<p>$ systemctl restart asterisk</p>
