Устанавливаем зависимости

ansible-galaxy install -r requirements.yml -p roles
Запускаем

ansible-playbook site.yml -i inventories/prod.yml