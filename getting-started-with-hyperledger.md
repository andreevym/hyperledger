# Getting Started with Hyperledger

### Сборка и запуск проекта fabric

Для простого примера мы будем использовать Docker.

выкачиваем проект:

У Hyperledger есть два репозитория на [GitHub](https://github.com/hyperledger/fabric) \(**READ-ONLY**\) и [gerrit.hyperledger.org](http://gerrit.hyperledger.org)

для Getting Started нам достаточно **READ-ONLY** репозитория на [GitHub](https://github.com/hyperledger/fabric)



> git clone https://github.com/hyperledger/fabric.git



собираем образы докера

> make docker



> docker-compose -f docker-compose.xml start



