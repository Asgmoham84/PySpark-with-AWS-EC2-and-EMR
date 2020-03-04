# PySpark-with-AWS-EC2-and-EMR
In this document we are setting up AWS (EC2 and EMR) for PySpark. If you are new to AWS and you want to know how you can set up an instance on it, and run your PySpark, please read on.

Steps:
1) Setting up an AWS EC2 Instance (free tier)
2) Create security key pairs in AWS for a secure connection to our instance
3) Downloading ans setting up PuTTY for connecting to the instance
4) Then on the instance we will:<br>
  •	Download Spark and then install it<br>
  •	Install Jupyter Notebook<br>
  •	Set up PySpark and connecting to it<br>
  •	Set up SSH Tunneling from our local machine to AWS <br>
5) Running Jupyter Notebook on our local browser<br><br>

We will also show how to set up a cluster on AWS EMR (Elastic Map Reduce) and run your PySpark code on the cluster using Zeppelin Notebook

