# devops-netology
Ok! it's work!  
oh may be don't work ( 

будут игнорироваться каталоги 
.terraform, файлы .tfstate, 
логи, .tfvars, которые могут содержать отправляемые данные, такие как
# пароль, закрытые ключи и другие секреты,
файлы override.tf
override.tf.json
* _override.tf
* _override.tf.json (файлы переопредления), 
файлы переопределения, которые вы хотите добавить в контроль версий, используя отрицательный шаблон ! example_override.tf,
файлы конфигурации CLI
.terraformrc
terraform.rc,
файлы tfplan для игнорирования вывода плана команды: terraform plan -out = tfplan
# пример: * tfplan *
В основном это системные файлы и настроек, которые не нужны в релизе. 

new line 
second line
!!!!!!

