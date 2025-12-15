# devops-repository
for study in devops
11


В директории terraform будут проигнорированыы все файлы состояния, переменных, провайдеров и т.д.

.terraform/
Игнорируется любая директория с именем .terraform и всё её содержимое в любом месте репозитория.
*.tfstate
Игнорируются все файлы, чьи имена заканчиваются на .tfstate.
*.tfstate.*
Игнорируются все файлы, у которых в имени есть подстрока .tfstate. (например, prod.tfstate.backup).
crash.log
Игнорируется файл с точным именем crash.log в любом каталоге.
crash.*.log
Игнорируются все файлы, имя которых:
начинается с crash., далее идёт произвольная последовательность символов (без /), и заканчивается на .log (например, crash.123.log, crash.test.log).
*.tfvars
Игнорируются все файлы, чьи имена заканчиваются на .tfvars.
*.tfvars.json
Игнорируются все файлы, чьи имена заканчиваются на .tfvars.json.
override.tf
Игнорируется файл с точным именем override.tf в любом каталоге.
override.tf.json
Игнорируется файл с точным именем override.tf.json в любом каталоге.
*_override.tf
Игнорируются все файлы, чьи имена:
содержат произвольную последовательность символов перед суффиксом _override.tf,
и заканчиваются на _override.tf (например, local_override.tf, dev_override.tf).
*_override.tf.json
Аналогично предыдущему правилу, но для имён, которые заканчиваются на _override.tf.json.
.terraform.tfstate.lock.info
Игнорируется файл с точным именем .terraform.tfstate.lock.info в любом каталоге.
.terraformrc
Игнорируется файл с точным именем .terraformrc в любом каталоге.
terraform.rc
Игнорируется файл с точным именем terraform.rc в любом каталоге.

<img width="831" height="1302" alt="image" src="https://github.com/user-attachments/assets/44700316-3b89-43ba-ad6f-2adffa949584" />
<img width="791" height="1212" alt="image" src="https://github.com/user-attachments/assets/8d59f213-f88f-4a3c-8bd1-c2ac004c04a8" />
<img width="615" height="668" alt="image" src="https://github.com/user-attachments/assets/e51c65aa-2373-455f-8d9e-6ae16fa35ca8" />
<img width="762" height="176" alt="image" src="https://github.com/user-attachments/assets/a8f32a13-2520-4b0c-9a08-e4f38ecbc686" />
