# Puppet
Puppet demo

//скачать VagrantFile

//скачать manifests/default.pp

vagrant up

vagrant ssh

which mongod

which redis-server

exit

vim Vagrantfile // раскомментить puppet

vim manifests/default.pp

vagrant reload

vagrant up --provision

vagrant ssh

ll // создалась папка my_directory

which redis-server

which mongod

ps -ef | grep mongodb

ps -ef | grep redis

exit

vim default.pp // закомментим запуск redis-service, ensure => absent

vagrant up --provision

vagrant ssh

ps -ef | grep redis // не запущен

vagrant exit

vagrant destroy
