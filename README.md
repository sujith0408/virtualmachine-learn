# virtualmachine-learn

ssh -i azureagent1_key.pem azureuser@public-ip

chmod 600 azureagent1_key.pem

ssh -i azureagent1_key.pem azureuser@public-ip

sudo apt update

sudo apt install docker.io

sudo usermod -aG docker azureuser

sudo systemctl restart docker


