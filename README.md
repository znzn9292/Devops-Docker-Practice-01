# Docker-Project

### Installation
<pre>
 cd /home
 git clone https://github.com/znzn9292/Docker-Project
 cd Docker-Project
</pre>

### Run
<pre>
 # Login For Private Docker Repository
 docker login
 docker pull znzn9292/docker-practice
 docker run -p 8080:8080 -v /home/ubuntu/Docker-Project/project:/usr/local/tomcat/webapps znzn9292/docker-practice
</pre>
