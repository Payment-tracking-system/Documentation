# ✅ Check Bills Bot

## 🛈 Что нужно знать

#### Для корректной установки проекта на вашем устройстве должен быть установлен Docker.
#### Что бы это сделать, вам необходимо посетить <a href='https://www.docker.com/products/docker-desktop/'>сайт представителя</a> и сделать все по инструкции
<details>
  <summary>Как проверить корректность установки?</summary>

  <br/>

> Просто введите команду. Если вам не выдало ошибку, то все окей `docker ps`
</details>

## 🛠 Установка

1. `clone` - для начала вам необходимо склонировать все репозитории из организации в рдну директорию. Для этого создайте папку на вашей виртуальной машине, перейдите в консоль из конкретной папки иначните по очереди клонировать репозитории:
+ `git clone https://github.com/Payment-tracking-system/Frontend.git` - Frontend
####
+ `git clone https://github.com/Payment-tracking-system/Backend.git` - Backend
####
+ `git clone https://github.com/Payment-tracking-system/Documentation.git` - Documentation

####
2. `Compose` - следующим этапом вам необходимо создать контейнер в своем docker с нашим проектом. Для этого перейдите в склонированную папку `Documentation` и открой и откройте там консоль. Введите следующую команду:
+ `docker-compose -f docker-compose.yml up --build -d`
####
3. John Quincy Adams

### ⚠️ WARNING
**·** Для корректной работы проекта необходимо, что бы все репозитории были склонированы и все пункты соблюдены.
