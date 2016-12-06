# dsi-camp-cnn
datascienceweekend.id camp 
DeepLearning using neon

if you don't have neon and ipython on your system
you can pull my docker [neon and ipython](https://hub.docker.com/r/sofianhw/docker-neon-ipython/)

[_install docker if you don't have docker on your system_](https://www.docker.com/products/overview)

$ docker pull sofianhw/docker-neon-ipython

$ docker run -t -p 8888:8888 --name neon sofianhw/docker-neon-ipython

open browser http://localhost:8888

if you wanna install it manually 
* [install neon](http://neon.nervanasys.com/index.html/installation.html)
* pip install ipython jupyter matplotlib
* ipython notebook --ip 0.0.0.0
