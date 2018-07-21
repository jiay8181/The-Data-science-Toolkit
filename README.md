# The-Data-science-Toolkit

1. Generating SSH Key: $ ssh-keygen

2. Amazon EC2: Launch instance -> Configure instance -> Select an existing key pair

3. Security Groups: A security group acts as a virtual firewall that controls the traffic for one or more instances.
   HTTP TCP 80 PostgreSQL TCP 5432 SSH TCP 22 Custom TCP Rule TCP 27016 HTTPS TCP 443

4. AWS Operating System: The OS We are using for AWS is Ubuntu Server 16.04 LTS

5. Docker InstallaTION: To access Ubuntu using terminal: $ ssh ubuntu@instance ip
                        To install docker: $ curl -sSL http://get.docker.com|sh
                                           $ sudo usermod -aG docker ubuntu
6. Use command Docker pull jupyter/datascience-notebook to obtain the correct image

7. Run data science notebook in the securied security environment using command docker run -p 80:8888 
   -v /home/ubuntu:/home/jovyan jupyter/datascience-notebook and then copy and paste token to ip:443 
   to open jupyter
8.Jupyter notebook uses token to authenticate requests.

9.

10. Using t2.micro, t2.small, t2.medium with memory of 1GB,2GB,4GB to run Jupyter Data Science Notebook
    for three months will cost $25.5,$50.52,$101.91 each. Totall $177.93.
                      
