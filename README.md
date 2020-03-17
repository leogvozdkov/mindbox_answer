# mindbox_answer

Ответ на тестовое задание mindbox на вакансию junior SRE

disclaimer: 

rmq.yaml - файл деплоя кластера rabbitMQ<br>
publisher.py и consumer.py - приложения на python для тестов (певый создаёт очереди и спамит рандомными строками, второй их читает).

Кластер rabbitmq был развернут на k8s в Яндекс.облаке с помощью persistent volume. До этого опыта ни с одной из технологий не имел.

Кластер доступен по ссылке - http://130.193.35.39:15672/ (пока не закончится тестовый период, креденшелы - в письме)

Использованные статьи и ресурсы:

https://habr.com/ru/company/true_engineering/blog/419817/<br>
https://kubernetes.io/docs/concepts/configuration/assign-pod-node/<br>
https://zupzup.org/k8s-rabbitmq-cluster/<br>
https://kubernetes.io/docs/concepts/workloads/controllers/statefulset/<br>
https://hub.docker.com/_/rabbitmq/<br>
https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.16<br>
https://www.rabbitmq.com/cluster-formation.html#peer-discovery-k8s

Скриншоты:

![вывод kubectl о кластере]
(https://github.com/leogvozdkov/mindbox_answer/blob/master/images/1.png?raw=true)

![скрин консоли rabbitMQ]
(https://github.com/leogvozdkov/mindbox_answer/blob/master/images/2.png?raw=true)
