sudo curl -L "https://github.com/docker/compose/releases/download/1.29.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
ls /usr/local/bin/
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose version  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
100 12.1M  100 12.1M    0     0  7063k      0  0:00:01  0:00:01 --:--:-- 46.1M
[root@ip-172-31-33-1 docker-compose]# ls /usr/local/bin/
docker-compose
[root@ip-172-31-33-1 docker-compose]# sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
[root@ip-172-31-33-1 docker-compose]# sudo chmod +x /usr/local/bin/docker-compose
[root@ip-172-31-33-1 docker-compose]# docker-compose version
docker-compose version 1.29.1, build c34c88b2
docker-py version: 5.0.0
CPython version: 3.7.10
OpenSSL version: OpenSSL 1.1.0l  10 Sep 2019
                                 
                                 
