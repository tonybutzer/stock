download:
	wget https://repo.anaconda.com/miniconda/Miniconda3-py39_4.9.2-Linux-x86_64.sh


install:
	bash Miniconda3-py39_4.9.2-Linux-x86_64.sh
	rm Miniconda3-py39_4.9.2-Linux-x86_64.sh


stocks:
	#conda deactivate
	conda env remove --name stocks
	conda env create --file stocks.yml
