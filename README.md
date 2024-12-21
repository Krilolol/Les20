Lesson 20


1. Створення StatefulSet для Redis-кластера
- Створив конфігураційні файли redis-pvc.yaml, redis-statefulset.yaml та redis-service.yaml.
- Запустив файли в терміналі.
![02](https://github.com/user-attachments/assets/f85113a6-aa33-4278-9a9b-32c3881db826)


- Поди запустилися та мають імена redis-0 та redis-1.
![03](https://github.com/user-attachments/assets/015382ba-eeae-4ef6-a4c0-6039670c4106)


- Зробив перевірку чи зберігаються дані після вилучення подів. Зберігаються, все працює коректно.


2. Налаштування Falco в Kubernetes за допомогою DaemonSet
- Створив конфігураційний файл falco-daemonset.yaml та запустив його.
- Перевірив запущені поди Falco.




