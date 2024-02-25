# oci-terraform-terminal
This repository builds a simple VCN infrastructure with terraform and oci terminal for information gathering

## API key set-up 
PURPOSE: The API will assist in setting up oci commandline interface
1. Login to your Oracle Cloud Console
2. Go to your profile and under your profile, click "My Profile"
3. On the left hand side, under "Resources", click on API keys
4. Click on "Add API Key"
5. Select "Generate API key pair" 
6. Download the "private" and "public" key 
   NOTE: make sure to store the API keys in an accessible folder (e.g. $HOME/.ssh)
7. Click "Add"
8. Make sure to copy the config file and save it in $HOME/.oci/config file
9. Once you copy the config file on your host, please point to the private key in the config file
