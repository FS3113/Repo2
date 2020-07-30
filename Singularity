Bootstrap: docker
From: ubuntu:18.04


%post
	apt-get -y update
	apt-get -y install python3 python3-pip
	pip3 install selenium sklearn urllib3 sklearn nltk


%files
	hello_world.py


%runscript
	python3 EducationToday/get_data_from_multiple_lists.py
