# UCS Manager Demo - Ansible Playbooks

## Setup

Create a virtual environment in Anaconda Python

'''bash
conda create -n ansible-2.9 'python=3.7'
conda activate ansible-2.9
pip install -r requirements.txt
'''

If the latest version of UCSM SDK is required, then follow these steps:

'''bash
git clone https://github.com/CiscoUcs/ucsmsdk.git
cd ucsmsdk
make install
cd ..
'''

## Requirements

- Python 3.7
- Ansible 2.9
- UCSM SDK > 0.9.8 (for UCS PE > 4.0.4a)

