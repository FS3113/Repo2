Bootstrap: docker
From: ubuntu:18.04


%post
	apt-get -y update
	apt-get -y install python3 python3-pip
	pip3 install selenium sklearn urllib3 sklearn nltk
	
%runscript
	python3 example.py
