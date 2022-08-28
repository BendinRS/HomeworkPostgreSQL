# Домашняя работа "PostgreSQL"

<details>
<summary>Описание</summary>

настроить hot_standby репликацию с использованием слотов  
настроить правильное резервное копирование  
Для сдачи работы присылаем ссылку на репозиторий, в котором должны обязательно быть  
Vagranfile (2 машины)  
плейбук Ansible  
конфигурационные файлы postgresql.conf, pg_hba.conf  
конфиг barman, либо скрипт резервного копирования.  

</details>


# Практика

+ Скрипт [test.sh](test.sh) запускает разворачивание и настройку ансиблом ВМ 
+ Роль [pg](roles/pg/) 
+ Конфиг [postgresql.conf](/roles/pg/files/postgresql.conf)    
+ Конфиг [pg_hba.conf ](/roles/pg/files/pg_hba.conf)  
+ Конфиг [barman ](/roles/pg/files/barman.conf) 