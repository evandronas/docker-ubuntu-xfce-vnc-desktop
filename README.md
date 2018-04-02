docker-ubuntu-xfce-vnc-desktop
=========================

### From Docker Repository

``
$ docker pull evandronas/ubuntu-xfce-vnc-desktop
``

### Build yourself

``
$ git clone https://github.com/evandronas/docker-ubuntu-xfce-vnc-desktop.git
$ docker build --rm -t evandronas/ubuntu-xfce-vnc-desktop docker-ubuntu-xfce-vnc-desktop
``

### Run

``
$ docker run -i -t -p 5900:5900 evandronas/ubuntu-xfce-vnc-desktop
``

Use vnc viewer to <YOUR IP>:5900


Trobleshooting
==================
You can find logs under /var/log/ in container.

