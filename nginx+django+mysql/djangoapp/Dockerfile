FROM python:3.5
#MySQL-Python必须得先安装这个库
RUN mkdir /video
#设置工作目录
WORKDIR /video
#将当前目录加入到工作目录中
ADD . /video
#install any needed pacakges in requirements.txt，你要把所有需要安装的Python模块加到这文件中。
RUN pip install -r requirements.txt
#对外暴露端口
EXPOSE 80 8000
#设置环境变量
ENV SPIDER=/video
