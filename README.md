# devCommands
This is a list of commands of all technologies that I have used.

<!-- Windows CMD --------------------------------- -->

# [Windows CMD]
#Delete all files under folder

`DEL /F/Q/S *.* > NUL`

#show apps per port

`netstat -ano | findstr :8080`

#killtask

`taskkill /PID 19176 /F`

#Program shutdown

`shutdown /s /f /t [timeInSeconds]`

#Cancel shutdown - Abort

`
shutdown.exe -a
`

# Copy file Windows to linux

`
scp [localWindowsPath] [remoteUsername]@[remoteIpAddress]:[remoteFileDestination]`


<!-- GIT --------------------------------- -->

# [GIT]

```
git clone [urlRepo]
git clone -b [brancheName] [urlRepo]
git stash
git stash list
git stash apply stash@{0}
git update-index --assume-unchanged  [pathToFiletoExclude]
git update-index --no-assume-unchanged [pathToFiletoInclude]

git rm -r --cached [path_to_your_folder/]
git status
git add .
git commit -m "text comments"
git push origin master
```

// Change Repository Server
```
git remote rm origin
git remote add origin [new URL]

git config --global user.name "UserName LastName"
git config --global user.email "nameEmail@domain.com"
git config --global [dnsServerNameForCredentialAuthority] Basic   
```
<!-- Tomcat --------------------------------- -->
# [Tomcat]

`{home_tomcat_directory}/bin/`

`$ catalina.bat run`


<!-- Maven--------------------------------- -->
# [Maven]
#Clean target/Build War
$ mvn clean install

#Clear all target files
$ mvn clean
#Build a WAR from Spring.io example - configure pom.xml
$ mvnw clean package

<!-- Gradle--------------------------------- -->
# [Gradle]

`
$ gradlew.bat tasks
$ gradlew.bat clean
$ gradlew.bat assemble
`

<!-- Linux--------------------------------- -->
# [Linux]
#Set Timezone

`$ sudo dpkg-reconfigure tzdata`

#Restart Network

`$ sudo netplan apply`

#Disk Space

`$ df -H`

<!-- openLDAP--------------------------------- -->
# [openLDAP]

`ldapsearch -x -LLL -H ldap:/// -b dc=example,dc=com dn`


<!-- npm--------------------------------- -->
# [npm]

#Quick Http Server

```
npm install http-server
http-server -p 8080
```
