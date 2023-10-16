
# README

---
## Role Name
  
repo_clickhouse_role  
  
---
## Description
  
Эта роль устанавливает на целевую машину сервис Clickhouyse и создает базу данных "logs"  
  
---
## Dependencies
  
None  
  
---
## Information
  

|Author|Company|License|Minimum Ansible Version|
| :---: | :---: | :---: | :---: |
|Nagibin Pavel|None|license (BSD, MIT)|2.1|

---

# Variable

## clickhouse_version
  
```

22.3.3.44
...
  
```
## clickhouse_packages
  
```

- clickhouse-client
- clickhouse-server
  
```
# Tasks

# install_clickhouse.yml


* Install clickhouse packages

# download_clickhouse.yml


* Download Clickhouse 1

* Download Clickhouse 2

# create_database.yml


* Wait for opening port 9000

* Create database