# SELinux-Permissive-Enforcing-Android-Termux
SELinux Permissive/Enforcing mode change Android with Termux Linux command line.

1. Root your phone superSU, Magisk etc..

2. Download Termux from google play

3. Open Termux
_____________________________________
4. Use root mode (Give root access termux)
  
 COMMAND: $ su   

5. Show what mode SELinux use now

COMMAND: $ getenforce

6. Set SELinux 
 
 COMMAND: $ setenforce 0

(Permissive)

COMMAND: $ setenforce 1

(Enforcing)
____________________________________

# Fungsi SELinux Permissive dan Enforcing

Enforcing: jika ada program, aplikasi, ataupun proses yang tidak memenuhi target policy yang sudah didefinisikan, maka SELinux akan memblok proses atau program tersebut

Perissive: jika ada program, aplikasi, ataupun proses yang tidak memenuhi target policy yang sudah didefinisikan, maka SELinux akan tidak memblok proses atau program tersebut, tetapi melaporkan ke dalam system log dan/atau selinux audit log sehingga dapat diakses laporannya dapat diakses oleh user (misalkan dengan setroubleshooter)

<a href="https://dedehamza.wordpress.com/2013/09/26/selinux-permissive-enforcing-apa-itu/" target="_blank">sumber</a>
