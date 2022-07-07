1. Установите Bitwarden плагин для браузера. Зарегестрируйтесь и сохраните несколько паролей.<br>

-	Ответ
![Bitwarden](https://github.com/davlyatov-ts/security/blob/master/Bitwarden.png)<br>
___
2. Установите Google authenticator на мобильный телефон. Настройте вход в Bitwarden акаунт через Google authenticator OTP.<br>

-	Ответ

![OTP](https://github.com/davlyatov-ts/security/blob/master/111.png)<br>
___
3. Установите apache2, сгенерируйте самоподписанный сертификат, настройте тестовый сайт для работы по HTTPS.<br>

-	Ответ

![install apache](https://github.com/davlyatov-ts/security/blob/master/apache2.png)<br>
![Cert](https://github.com/davlyatov-ts/security/blob/master/openssl-req.png)<br>
![https](https://github.com/davlyatov-ts/security/blob/master/https.png)<br>
___
4. Проверьте на TLS уязвимости произвольный сайт в интернете (кроме сайтов МВД, ФСБ, МинОбр, НацБанк,<br>
 РосКосмос, РосАтом, РосНАНО и любых госкомпаний, объектов КИИ, ВПК ... и тому подобное).<br>

-	Ответ

![TLS](https://github.com/davlyatov-ts/security/blob/master/jet.png)<br>
___
5. Установите на Ubuntu ssh сервер, сгенерируйте новый приватный ключ.<br> 
Скопируйте свой публичный ключ на другой сервер. Подключитесь к серверу по SSH-ключу.<br>

-	Ответ<br>

**ssh-keygen**
![ssh-keygen](https://github.com/davlyatov-ts/security/blob/master/ssh-gen.png)<br>

**ssh-copy-id**
![ssh-copy-id](https://github.com/davlyatov-ts/security/blob/master/copy.png)<br>

**ssh**
![ssh](https://github.com/davlyatov-ts/security/blob/master/ssh-conn.png)<br>
__
