# Безлимитный интернет на Vodafone
(![Alt Text](https://media.giphy.com/media/rwMofHqKKMLHW/giphy.gif)

## Требования:
1. Нулевой баланс на счету
2. TLS Tunnel (работает только на Android)
3. SNI профиль который я оставил чуть ниже
4. Мозг
## Использование:
1. Скачиваем TLS Tunnel
2.![image](https://user-images.githubusercontent.com/81299684/112294781-dc5f8880-8c9b-11eb-8087-a9e62f057384.png)
3. Входим в приложение
4. Выбираем способ подключения:
- **Пользовательский SNI**
![image](https://user-images.githubusercontent.com/81299684/112294983-1df03380-8c9c-11eb-87ed-c9859f6cfbe8.png)
5. Вставляем туда код который находится ниже
6.**CONNECT [host_port] [protocol][crlf]Host: speedtest.vodafone.ua[crlf]X-Online-Host: speedtest.vodafone.ua[crlf]X-Forward-Host: speedtest.vodafone.ua[crlf]Connection: Keep-Alive[crlf]User-Agent: [ua][crlf]CONNECT [host_port] [protocol][crlf][crlf]**
7. Порт оставляем таким-же, для более быстрого интернета выбираем **Бразилию**
8. Включаем передачу данных и жмем на кнопку **"НАЧАТЬ"**
9. Пользуемся бесплатным безлимитом ✅
