FROM telegraf:1.12.5

RUN apt update

RUN apt install ipmitool -y

ADD telegraf.conf /etc/telegraf/telegraf.conf