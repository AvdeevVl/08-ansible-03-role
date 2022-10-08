Playbook с ролями для установки Java, Elasticsearch и Kibana  
- Устанавливаем зависимости  
`ansible-galaxy install -r requirements.yml -p roles`
- Запускаем  
`ansible-playbook site.yml -i inventory/prod.yml`