# pytorch_determinism_testing

The requirements.txt file contains the pytorch version compatible with cuda 11.2 for use with the rtx 3090 so you need to install your corresponding pytorch version yourself.

after cloning:

1. python3 -m venv venv
2. . venv/bin/activate
3. pip install --upgrade pip
4. pip install -r requirements.txt
(5. install pytorch depending on your cuda version and graphics card)
6. jupyter notebook
7. run all and check the output loss and weight matrices for two separate runs
