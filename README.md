# What is SELinux Permissive and Enforcing

SELinux Permissive and Enforcing Functions
Enforcing: if there is a program, application, or process that does not meet the defined policy target, then SELinux will block the process or program

Permissive: if there is a program, application, or process that does not meet the defined policy target, then SELinux will not block the process or program, but report it to the system log and/or selinux audit log so that the report can be accessed by the user ( e.g. with setroubleshooter)

<a href="https://dedehamza.wordpress.com/2013/09/26/selinux-permissive-enforcing-apa-itu/" target="_blank">sumber</a>

# Apa itu SELinux Permissive dan Enforcing

Fungsi SELinux Permissive dan Enforcing
Enforcing: jika ada program, aplikasi, ataupun proses yang tidak memenuhi target policy yang sudah didefinisikan, maka SELinux akan memblok proses atau program tersebut

Permissive: jika ada program, aplikasi, ataupun proses yang tidak memenuhi target policy yang sudah didefinisikan, maka SELinux akan tidak memblok proses atau program tersebut, tetapi melaporkan ke dalam system log dan/atau selinux audit log sehingga dapat diakses laporannya dapat diakses oleh user (misalkan dengan setroubleshooter)

# How to change SELinux?
_____________________________________
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
