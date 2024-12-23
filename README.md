Требования к программному обеспечению:
Разрабатываемое ПО рассчитано на функционирование в следующей программной среде: Microsoft Windows 10 х64 с поддержкой среды выполнения .NET Framework v4.7.2.
Требования к техническому обеспечению:
Минимальный объем свободного пространства для установки ПО должен составлять 15 Mб.

1.3 Руководство пользователя
Запустить установщик Cryptoprovider.msi. Установить.
Рекомендуется запустить с правами администартора для установки контекстного меню.
При первом запуске будет предложено окно для ввода пароля для криптоконтейнера (рис.1). Внимание! Пароль необходимо запомнить пользователю, так как восстановлению не подлежит.
 ![image](https://github.com/user-attachments/assets/9e924dfe-3bae-4e9c-ba91-cca71fc76a9a)

Рис. 1. Окно для ввода парольной фразы.

После успешного ввода пароля, появится окно загрузки и будет реализована генерация открытого (public_key.crt) и закрытого (encrypted_key.pem) ключей.
Пользовательский интерфейс:
 ![image](https://github.com/user-attachments/assets/e2451b92-b46f-4d09-a677-bd1f6ebb79f8)

Функционал:
1. «Обновить ключ» - вставляет открытый ключ из вашего файла открытого ключа.
2. «Заменить ключ» - полная замена открытого и закрытого ключей. ПО предложит ввести новый пароль и сгенерирует новые ключи.
3. «Скопировать сертификат» - скопирует в буфер обмена файл публичного ключа.
4. «Вставить сертификат» - предложит выбрать путь к файлу с новым открытым ключом в формате .crt.
5. «Показать сертификат» - покажет директорию расположения открытого ключа.
6. «Выбрать файл» - предложит выбрать путь для файла и выведет его на экран.
7. «Шифровать» - предложит ввести имя для зашифрованного файла, путь его сохранения, пароль для криптоконтейнера и шифрует файл (.zip).
8. «Дешифровать» - предложит выбрать путь для сохранения файла, пароль для криптоконтейнера и дешифрует файл.
9. «Хеш файла» - выведет окно с хешем выбранного файла.
Контекстное меню:
1. «Получить Хеш» – выведет окно с хешем выбранного файла.
2. «Шифровать файл» - предложит ввести имя для зашифрованного файла, путь его сохранения, пароль для криптоконтейнера и шифрует файл(.zip).
