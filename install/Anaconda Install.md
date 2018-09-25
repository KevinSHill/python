## Download Anaconda File 

1. Go to Anaconda page for newest version: https://www.anaconda.com/download/
2. Go to root user: sudo su
3. navigaate to /opt
4. wget the URL of the lastest version from step 1

## Install and Upgrade

1. Run: bash Anaconda_latestVersion-Linux-x86_64.sh
2. Follow the defaults execpt specify the location to be: /opt/anaconda3
3. Run: conda upgrade --all

## Include Conda on User Bash
1. Include the following for each user: echo 'export export PATH=/opt/anaconda3/bin:$PATH' >> ~/.bashrc

## Helpful webpages:
https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/

