# 13-04-kubernetes-config-helm


В тот же namespace не ставится, что вполне логично, т.к. сервисы имеют такие же имена.
ТОлько если менять имя сервисов типа frontend_1.2, 
но управлять и дебажить проблемы очень неудобно будет

![img.png](img.png)

В разных namespace работает 

![img_1.png](img_1.png)

Версия образа в namespace=app1

![img_3.png](img_3.png)

Запущенные pod в namespace=app1

![img_6.png](img_6.png)

Версия образа в namespace=app2

![img_4.png](img_4.png)

Запущенные pod в namespace=app2

![img_5.png](img_5.png)