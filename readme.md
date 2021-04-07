Консольное приложение 3DES
Для запуска программы необходимо иметь jre не ниже 1.8

Сгенерировать ключ: 3DES.exe genkey password outputFile   

Зашифровать файл: 3DES.exe encrypt inputFile keyFile outputFile mode

Дешифровать файл: 3DES.exe decrypt inputFile keyFile outputFile mode

mode:
    ECB
    CBC
    CTR
