### Doctor
---

https://github.com/minio/doctor
```
wget https://raw.githubusercontent.com/minio/doctor/master/docker-compose.yml
wget https://raw.githubusercontent.com/minio/doctor/master/.env

RAILS_ENV=production docker-compose up -d

docker-compose up -d
docker ps
docker exec docapp bundle exec rake db:setup
curl http://localhost:3000/

git clone https://github.com/minio/doctor.git
cd doctor
bundle install
rake db:drop
rake db:setup
rails s
curl http://localhost:3000/

```







