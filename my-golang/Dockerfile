FROM ubuntu:18.04
 
RUN rm -rf /etc/apt/sources.list


RUN echo 'deb http://mirrors.aliyun.com/ubuntu/ bionic main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo 'deb-src http://mirrors.aliyun.com/ubuntu/ bionic main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo 'deb http://mirrors.aliyun.com/ubuntu/ bionic-security main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo 'deb-src http://mirrors.aliyun.com/ubuntu/ bionic-security main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo 'deb http://mirrors.aliyun.com/ubuntu/ bionic-updates main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo 'deb-src http://mirrors.aliyun.com/ubuntu/ bionic-updates main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo 'deb http://mirrors.aliyun.com/ubuntu/ bionic-proposed main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo 'deb-src http://mirrors.aliyun.com/ubuntu/ bionic-proposed main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo 'deb http://mirrors.aliyun.com/ubuntu/ bionic-backports main restricted universe multiverse' >> /etc/apt/sources.list
RUN echo 'deb-src http://mirrors.aliyun.com/ubuntu/ bionic-backports main restricted universe multiverse' >> /etc/apt/sources.list

RUN apt-get update

RUN apt-get install -y golang emacs

CMD ["/bin/bash"]
