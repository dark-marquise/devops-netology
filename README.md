# devops-netology
Ok! it's work!  
oh may be don't work ( 

Ответ на задание : 
будут игнорироваться файлы и каталоги, такие как: 
**/.terraform/* - каталог, при совпадаениие во всех каталогах
crash.log - файлы логов 
*.tfvars - все файлы, которые могут содеражть отправляемые данные( пароли, ключи) 
override.tf override.tf.json  - эти файлы 
*_override.tf 
*_override.tf.json - люьые файлы оканчивающие так. 
! example_override.tf - при использовании отрицательного шаблона, можно включить любой соответствующий файл, исключенный предыдущим шаблоном
.terraformrc terraform.rc  -файлвы конфигруации CLI 

test ide 2


