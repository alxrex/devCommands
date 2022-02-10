<!-- Linux--------------------------------- -->
# [Linux]
#Set Timezone

`$ sudo dpkg-reconfigure tzdata`

#Restart Network

`$ sudo netplan apply`

#Disk Space

`$ df -H`




# Java JRE

`sudo update-alternatives --config java`

# Java JDK
`sudo update-alternatives --config javac`



# JAVA_HOME - Add Path Variable 

sudo nano /etc/environment

JAVA_HOME="/usr/lib/jvm/java-8-openjdk-amd64"
JAVA_HOME="/usr/lib/jvm/java-11-oracle"


source /etc/environment

echo $JAVA_HOME
