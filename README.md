# hexaa-docker

Repository for HEXAA docker container files.

This project is WIP.

Run  using

'''

sudo docker run --link some_running_mysql_container:mysql -v /hexaa_docker_directory/parameters.yml:/opt/hexaa-backend/app/config/parameters.yml -v /hexaa_docker_directory/hexaa_admins.yml:/opt/hexaa-backend/app/config/hexaa_admins.yml -v /hexaa_docker_directory/hexaa_entityids.yml:/opt/hexaa-backend/app/config/hexaa_entityids.yml -v /hexaa_docker_directory/hexaa_test.conf:/etc/apache2/sites-enabled/hexaa.conf -d hexaa-backend

'''