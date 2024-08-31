# ruby_on_rails_gerlessver
git clone ...
https://github.com/juniormesquitadandao/gerlessver/tree/master/ruby_on_rails
cd project
ARG_USER_UID=$(id -u) ARG_USER_GID=$(id -g) docker compose config
ARG_USER_UID=$(id -u) ARG_USER_GID=$(id -g) docker compose build
docker compose up -d
docker compose exec app bash
cat /etc/hosts | grep dockerhost
echo > /dev/tcp/dockerhost/5432 && echo "Postgresql is running"
echo > /dev/tcp/dockerhost/6379 && echo "Redis is running"
bundle
npm install
rails db:create
RAILS_ENV=test rails db:create
rails c
Redis.new.keys
exit
rails s
git status
git add .
git commit -m 'update'
git push
exit
docker compose down
