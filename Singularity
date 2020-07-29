Bootstrap: docker
From: ubuntu:18.04


%post
	apt-get -y update
	apt-get -y install python3 python3-pip
	pip3 install selenium


%files
	hello_world.py


%runscript
	python3 hello_world.py
