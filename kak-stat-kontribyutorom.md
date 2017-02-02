# ![](/assets/logo_hl_new.png)

# Как стать контрибьютором?

![](/assets/lflogo2016_color.png)

# 10

Нам необходимо завести аккаунт в [Linux Foundation](https://www.linuxfoundation.org/)

url: [https://identity.linuxfoundation.org/user](https://identity.linuxfoundation.org/user)

# 9

Залогиниться:

Выбрать задачу можно несколькими способами найти задачу в JIRA [http://jira.hyperledger.org/](http://jira.hyperledger.org/) попросить задачу в Slack

# 8

**Взять задачу в работу** [http://jira.hyperledger.org/](https://www.gitbook.com/book/andreevym/hyperledger-fabric/edit#)

Залогиниться в [https://gerrit.hyperledger.org/](https://gerrit.hyperledger.org/)

# 7

добавить \(ssh\) ключ

[https://gerrit.hyperledger.org/r/\\#/settings/ssh-keys](https://gerrit.hyperledger.org/r/\#/settings/ssh-keys)

# 6

выкачать проект  \(LFID - ваш Linux Foundation id. Пример:JonHon\)

git clone ssh://LFID@gerrit.hyperledger.org:29418/**ONE-OF-PROJECTS**

# 5

в папку .git/hooks добавить hook, для генерации Change-Id

> scp -p -P 29418 LFID@gerrit.hyperledger.org:hooks/commit-msg fabric/.git/hooks/

# 4

выполнить задачу

# 3

Сделать commit

> git commit -s -m ""

### Правила для сообщения при коммите:

1\) Длина строки не больше 50 символов

2\) Наличие Change-Id \(это мы решили на шаге 1\)

3\) Наличие Signed-off-by: xx \(это мы решили на шаге 2 указав -s\)

## 2

Сделать пул реквест
git push origin HEAD:refs/for/WIP_fabric_v1

Когда вы отправите изменения в gerrit вам нужно будет добавить кого-нибудь из reviewers.
Для этого зайтиде на страницу maintainers.md вашего проекта - email адреса
By `reviewers` press the `Add...` button

перевести статус задачи в JIRA [http://jira.hyperledger.org/](https://www.gitbook.com/book/andreevym/hyperledger-fabric/edit#)

# 1

отвечать на комментарии и дойти до **merge -&gt;** в ветку **master**

