# Puppet
Puppet demo

vagrant init ubuntu/trusty64

vagrant up

vagrant ssh

which mongod

which redis-server

exit

//скачать VagrantFile

//скачать manifests/default.pp

vim Vagrantfile

cd manifests

vim default.pp

vagrant reload

vagrant ssh

ll // создалась папка my_directory

which redis-server

which mongod

ps -ef | grep mongodb

ps -ef | grep redis

exit

vim default.pp // закомментим запуск redis-service, ensure => absent

vagrant provision

vagrant ssh

ps -ef | grep redis // не запущен

vagrant exit

vagrant destroy
