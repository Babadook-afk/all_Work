# MongoDB-NoSQL-Вот README только с тем, что выполнено на вашем фото:

```markdown
# MongoDB в Docker

## 1. Запуск контейнера

```bash
docker run -d \
    --name my-mongo \
    -p 27017:27017 \
    mongo:latest
```

![alt text](image.png)

---

## 2. Подключение к MongoDB

```bash
docker exec -it my-mongo mongosh
```

![alt text](image-1.png)

---

## 3. Команды MongoDB

### Показать все базы данных
```javascript
show dbs
```
![alt text](image-2.png)
### Показать текущую базу данных
```javascript
db
```
![alt text](image-3.png)
### Переключиться на базу данных
```javascript
use testdb
```
![alt text](image-4.png)
<!-- 📸 ФОТО 3: скриншот выполнения команд -->

---

## 4. Выход

```javascript
exit
```
![alt text](image-5.png)