## Jaringan (Network)

### Model dasar

* Model OSI dan TCP/IP : memahimi lapisan layer dan fungsi utama dari setiap lapisan.

---


### Protokol penting

* TCP/UDP : memahami perbedaan dasar dan kapan masing masing digunakann 
* HTTP/HTTPS : memahami siklus request/response dan pentingnya enkripsi (TLS/SSL)
* DNS : memahami cara kerja resolusi nama dan log DNS sebagai sumber penting dalam malware
* DHCP, ARP, ICMP : memahami protokol yang digunakan untuk konfigurasi dan diagnostik 


---

### Konsep penting 

* Subnetting dan routing : memahami bagaimana jaringan dibagi dan bagaimana paket menemukan jalannya 
* port umum : mengetahui port standar yang digunakan aplikasi penting (80,443,53,21,22,23,3389,25,110,dll)


---


## Windows internals 

### EventLog

* mengetahui jenis" event log yang ada (Application, system, security)
* event ID : 4624/4625 : login berhasil / gagal
* event ID : 4740/4720 : akun dikunci dan akun dibuat
* auditpolicy : memahami cara konfigurasi audit untuk mendapatkan log yang diperlukan 
* registry : memahami struktur dasar registry dan lokasi kunci yang sering dimanfaatkan malware untuk persistensi (misalnya, Run keys)
* proses dan service : mengetahui cara memeriksa proses yang berjalan dan layanan windows 


---

## Linux internals 

### Log

* struktur file : memahami struktur direktori standar misal: 
```terminal
/etc, /var/log, /bin
```
* log penting 
```terminal
/var/log/auth.log atau /var/log/secure
```
* systemd journal atau syslog
* perintah dasar 
```terminal 
ls, cd, grep, awk, cat, less
ps, top, netstat/ss, ifconfig/ip a
```
<<<<<<< HEAD:5 pilar kopetensi inti/Jaringan dan OS.md
* hak akses : memahami konsep ``` chmod ``` (hak akses) dan ``` chown ``` (kepemilikan file)
=======
* hak akses : memahami konsep ``` chmod ``` (hak akses) dan ``` chown ``` (kepemilikan file)
>>>>>>> ae5d8f5a02ca394f4e078d95ba05f4f165e58b86:Jaringan dan OS.md
