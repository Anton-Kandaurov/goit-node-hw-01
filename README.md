NodeJS_HW01
Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
node index.js --action="list" https://monosnap.com/file/EYYYUAJwhct2pVUwoW6QKUTNTI6lVo

Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.
node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6 https://monosnap.com/file/U36Uau1ibUCn9yL9GbX2rqcmUuBk9S

Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту
node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22 https://monosnap.com/file/AVAM6knTEPZnuU6acGQY922YC8x2jL

Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH https://monosnap.com/file/TYTjd1nQhD3ycVgDfS5hpQbznhjF7b