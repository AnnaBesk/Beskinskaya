Делаем ssh:
1) прописываем все config
2) генерируем ключ: ssh-keygen -t ed25519 -C "your_email@example.com"
3) если windows: добавляем shh agent: eval "$(ssh-agent -s)"

На сайт добавляем ссылку:
1) Заходим в настройки -> ключи SSH -> new key -> копируем текст из файла с разрешением .pub

Клонируем репозиторий: git clone git@github.com:username/repository.git
ссылку берем с сайта GitHub SSH ссылка