Create a virtual env, either python -m venv or conda init, conda activate (preferred and used for this project)

(conda create --name env_name python=3.10) - any stable version between 3.9 and 3.11. Some python libraries like torch, transformers are unstable with python 3.12+

install dependencies from the requirements.txt 

(pylmza is native for python 3.3+ versions)
Depending on the python versions, current OS and GPU settings, follow this url to get the command to install torch
http://pytorch.org/get-started/locally/

(MacOS - Default: pip3 install torch torchvision torchaudio)

(experimenting with a text file - david copperfield book)
Download a sample book as a text file - https://www.gutenberg.org/

