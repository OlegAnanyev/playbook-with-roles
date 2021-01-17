# Ansible-проект для установки Java + Elastic + Kibana через roles

Установить зависимости:
```
ansible-galaxy install -r requirements.yml
```

Запустить плейбук:
```
ansible-playbook -i inventory/prod.yml --ask-pass --ask-become-pass site.yml
```