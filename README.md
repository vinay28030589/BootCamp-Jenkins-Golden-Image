# jenkins_goldenimage

<html><body><h1 style="font-size:50px;color:blue;">WEZVA TECHNOLOGIES (ADAM) | <font style="color:red;"> www.wezva.com | <font style="color:green;"> +91-9739110917 </h1>
<h1> Subscribe to our youtube channel: 
<a href="https://www.youtube.com/c/DevOpsLearnEasy">https://www.youtube.com/c/DevOpsLearnEasy</a> </h1>
</body></html>

## Ensure Packer 1.8.7 is available - the script is tested against this version at the time of creation ##
 $ wget https://releases.hashicorp.com/packer/1.8.7/packer_1.8.7_linux_amd64.zip
 $ unzip packer_1.8.7_linux_amd64.zip -d /usr/local/bin


## Update the Packer JSON file with a security group id which allows port 2049 on TCP in both inbound/outbound rules
## Also ensure the EFS is created using the same security group 
