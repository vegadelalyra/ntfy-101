# ntfy-101    
Learning to generate push notifications for free on server side with open-source NTFY server hosted on a docker image running inside a Google Cloud Platform Virtual Machine    

## Create a Virtual Machine on any Cloud Provider     

### Getting a Google Cloud Platform Virtual Machine free instance!   

Googling "Google Cloud Platform Virtual Machine Free Tier" you will have access to [this link](https://cloud.google.com/free/docs/free-cloud-features#compute) where you can read the Free Tier characteristics you must fulfill. GCP will show charges at your side but you will never get really charged, it's like a catchy bug.

<img width="544" alt="image" src="https://github.com/vegadelalyra/ntfy-101/assets/77188420/2f08bc4d-fe4d-47de-896d-0d437c742bd2">    

## Installing Dokcer on your Virtual Machine    

Once you are at the Shell of your VM instance, you can run for Linux systems:   

#### sudo apt update
#### sudo apt install docker.io -y
#### sudo docker run -p 80:80 -itd binwiederhier/ntfy serve
