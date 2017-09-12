## Laboratory work II

Данная лабораторная работа посвещена изучению утилит для разработки проектов

## Tasks

- [x] 1. Ознакомиться со ссылками учебного материала
- [x] 2. Выполнить инструкцию учебного материала
- [x] 3. Составить отчет и отправить ссылку личным сообщением в **Slack**

  ВЫПОЛНЯЯ ИНСТРУКЦИЮ УЧЕБНОГО МАТЕРИАЛА: 
 
 ```
$ export GITHUB_USERNAME=GolubDobra

$ export GIST_TOKEN=390e4d6a8a0a323d04d567f76e88e6316755b42a

$ alias edit=subl


$ cd ~

$ mkdir -p workspace/labs/projects/

$ mkdir -p workspace/labs/tasks/

$ mkdir -p workspace/labs/reports/

$ cd ~/workspace/labs/

$ export LAB_NUMBER=02

$ git clone https://github.com/tp-labs/lab${LAB_NUMBER} tasks/lab${LAB_NUMBER}

Клонирование в «tasks/lab02»…
remote: Counting objects: 28, done.
remote: Total 28 (delta 0), reused 0 (delta 0), pack-reused 28
Распаковка объектов: 100% (28/28), готово.

$ mkdir reports/lab${LAB_NUMBER}

$ cp tasks/lab${LAB_NUMBER}/README.md reports/lab${LAB_NUMBER}/REPORT.md

$ cd reports/lab${LAB_NUMBER}

$ edit REPORT.md
```
