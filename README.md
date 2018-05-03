### Supported tags and respective **``Dockerfile``** links
- `latest`, `5.7-hap` [(Dockerfile)](https://github.com/eliu/docker-mysql/blob/master/5.7-hap/Dockerfile)

### Base image: 
- `mysql:5.7`

### Features:
- Update mysql configurations for HAP:

  ```properties
  [client]
  default-character-set=utf8
  
  [mysql]
  default-character-set=utf8
  
  [mysqld]
  lower_case_table_names=1
  max_connections=500
  collation-server=utf8_unicode_ci
  init-connect='SET NAMES utf8'
  character_set_server=utf8
  ```

  
