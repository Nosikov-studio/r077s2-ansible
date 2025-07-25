# r077s2-ansible
ЗАВИСИМОСТИ УСТАНАВЛИВАЮТСЯ ВРУЧНУЮ (без ansible), т.к. мощности сервера (100% CPU) не хватает (в моем случае).

Установите pip для python3.
Для большинства Linux-дистрибутивов:

bash
apt-get update
apt-get install python3-pip
Проверьте, что теперь pip работает:

bash
python3 -m pip --version
Убедитесь, что у вас установлен python3-dev.
Некоторые npm-пакеты могут использовать заголовочные файлы Python для сборки native модулей:

bash
apt-get install python3-dev
После установки pip повторно выполните npm install

bash
npm install