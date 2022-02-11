# 08-ansible-02-playbook

1) Описание playbook
    - Playbook устанавливает и настраивает elasticsearch и kibana.
    - В playbook используются теги java, python, elastic, kibana.
2) Тестовое окружение
    - Два docker-контейнера на базе centos реализованы на docker-compose
    - Развертывание контейнеров и запуск playbook осуществляются bash скриптом deploy_script 
    - Прежде запуска bash скрипта необходимо скачать дистрибутив java(jdk-11.0.14_linux-x64_bin.tar.gz) и положите 
    его в директорию ./files

