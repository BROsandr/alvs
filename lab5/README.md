# Лабораторная работа №5

1.  ## Задание 1.

    > Настройте ansible на серверной машине. В качестве клиентов выберете обе машины
    > – сервер и клиент.

    Внесем ip машин в файл `/etc/ansible/hosts`:

    ![Alt text](image.png)

2.  ##  Задание 2.

    > Проверьте доступность всех устройств с помощью команды ping используя запуск скрипта ansible

    **КОД**:

    ```bash
    ansible -m ping all
    ```

    **OUTPUT**:

    ![Alt text](image-1.png)

    **ВЫВОД**: Все машины доступны.

3.  ## 