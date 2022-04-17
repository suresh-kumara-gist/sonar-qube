
www-data@87e3be48397e:/app$ history 
    1  apt-get install yara 
    2  sudo apt-get install yara 
    3  yum install yara  
    4  git clone git@github.com:VirusTotal/yara.git 
    5  cd yara 
    6  YACC=bison ./configure 
    7  cd ..
    8  cd admin/
    9  ls -la
   10  find . -type f -perm 0444 -name ".htaccess" -exec echo rm {} \; 
   11  git status 
   12  cd ..
   13  ls -la
   14  exit 
   15  ls -la 
   16  mv sonar-scanner/ /sonar-scanner/
   17  sudo mv sonar-scanner/ /sonar-scanner/
   18  ls -la /
   19  cd /tmp/
   20  cd -
   21  sudo mv sonar-scanner/ /tmp/sonar-scanner/
   22  mv sonar-scanner/ /tmp/sonar-scanner/
   23  cd /tmp/sonar-scanner/ 
   24  ls 
   25  echo $PATH 
   26  cd bin/
   27  export PATH=$PATH:/tmp/sonar-scanner/bin
   28  echo $PATH 
   29  export PATH=$PATH:/tmp/sonar-scanner
   30  echo $PATH 
   31  sonar-scanner
   32  cd /app/
   33  sonar-scanner   -Dsonar.projectKey=mktyagi   -Dsonar.sources=.   -Dsonar.host.url=http://localhost:9000   -Dsonar.login=723e1babbb64e9f0952ccc5f005170dcc614539c 
   34  sonar-scanner   -Dsonar.projectKey=mktyagi   -Dsonar.sources=.   -Dsonar.host.url=http://192.168.1.104:9000   -Dsonar.login=723e1babbb64e9f0952ccc5f005170dcc614539c 
   35  history 



cd sonar-qube 
docker-compose up -d 
localhost:9000
login username: admin password: admin
create project
generate token 

cd sonar-scanner 
lando init 
select  current directory , lamp receipe , 
lando start 
add bin variable to $PATH 
sonar-scanner   -Dsonar.projectKey=<projectname>   -Dsonar.sources=/app   -Dsonar.host.url=http://<ipadress-of-host>:9000   -Dsonar.login=<token>
