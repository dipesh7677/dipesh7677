dipesh@webhost:~$ nano configure-host.sh
dipesh@webhost:~$ chmod +x configure-host.sh
dipesh@webhost:~$ nano lab3.sh
dipesh@webhost:~$ chmod +x lab3.sh
dipesh@webhost:~$ ./lab3.sh
ssh: Could not resolve hostname server1-mgmt: Temporary failure in name resolution
lost connection
ssh: Could not resolve hostname server1-mgmt: Temporary failure in name resolution
ssh: Could not resolve hostname server2-mgmt: Temporary failure in name resolution
lost connection
ssh: Could not resolve hostname server2-mgmt: Temporary failure in name resolution
./configure-host.sh: line 49: /etc/hosts: Permission denied
./configure-host.sh: line 49: /etc/hosts: Permission denied
dipesh@webhost:~$ sudo nano /etc/hosts
[sudo] password for dipesh:
dipesh@webhost:~$ sudo nano /etc/hosts
dipesh@webhost:~$ sudo echo "192.168.16.3   loghost" >> /etc/hosts
sudo echo "192.168.16.4   webhost" >> /etc/hosts
-bash: /etc/hosts: Permission denied
-bash: /etc/hosts: Permission denied
dipesh@webhost:~$ sudo nano /etc/hosts
dipesh@webhost:~$ ping server1-mgmt
ping server2-mgmt
PING server1-mgmt (192.168.16.3) 56(84) bytes of data.
From webhost (192.168.16.1) icmp_seq=1 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=2 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=3 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=4 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=5 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=6 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=7 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=8 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=9 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=10 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=11 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=12 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=13 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=14 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=15 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=16 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=17 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=18 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=19 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=20 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=21 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=22 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=23 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=24 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=25 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=26 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=27 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=28 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=29 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=30 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=31 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=32 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=33 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=34 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=35 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=36 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=37 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=38 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=39 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=40 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=41 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=42 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=43 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=44 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=45 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=46 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=47 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=48 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=49 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=50 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=51 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=52 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=53 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=54 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=55 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=56 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=57 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=58 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=59 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=60 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=61 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=62 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=63 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=64 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=65 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=66 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=67 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=68 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=69 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=70 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=71 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=72 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=73 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=74 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=75 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=76 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=77 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=78 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=79 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=80 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=81 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=82 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=83 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=84 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=85 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=86 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=87 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=88 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=89 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=90 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=91 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=92 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=93 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=94 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=95 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=96 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=97 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=98 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=99 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=100 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=101 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=102 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=103 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=104 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=105 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=106 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=107 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=108 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=109 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=110 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=111 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=112 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=113 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=114 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=115 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=116 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=117 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=118 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=119 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=120 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=121 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=122 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=123 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=124 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=125 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=126 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=127 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=128 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=129 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=130 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=131 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=132 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=133 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=134 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=135 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=136 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=137 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=138 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=139 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=140 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=141 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=142 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=143 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=144 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=145 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=146 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=147 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=148 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=149 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=150 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=151 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=152 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=153 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=154 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=155 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=156 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=157 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=158 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=159 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=160 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=161 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=162 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=163 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=164 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=165 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=166 Destination Host Unreachable

From webhost (192.168.16.1) icmp_seq=167 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=168 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=169 Destination Host Unreachable

From webhost (192.168.16.1) icmp_seq=170 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=171 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=172 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=173 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=174 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=175 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=176 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=177 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=178 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=179 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=180 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=181 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=182 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=183 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=184 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=185 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=186 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=187 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=188 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=189 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=190 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=191 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=192 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=193 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=194 Destination Host Unreachable
^C
--- server1-mgmt ping statistics ---
196 packets transmitted, 0 received, +194 errors, 100% packet loss, time 198278ms
pipe 4
PING server2-mgmt (192.168.16.4) 56(84) bytes of data.
From webhost (192.168.16.1) icmp_seq=1 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=2 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=3 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=4 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=5 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=6 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=7 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=8 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=9 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=10 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=11 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=12 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=13 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=14 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=15 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=16 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=17 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=18 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=19 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=20 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=21 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=22 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=23 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=24 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=25 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=26 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=27 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=28 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=29 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=30 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=31 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=32 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=33 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=34 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=35 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=36 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=37 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=38 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=39 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=40 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=41 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=42 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=43 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=44 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=45 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=46 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=47 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=48 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=49 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=50 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=51 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=52 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=53 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=54 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=55 Destination Host Unreachable
From webhost (192.168.16.1) icmp_seq=56 Destination Host Unreachable
^C
--- server2-mgmt ping statistics ---
57 packets transmitted, 0 received, +56 errors, 100% packet loss, time 61826ms
pipe 4
dipesh@webhost:~$
