# Porn Blocker
В этом репозитории храниться host файл с коллекцией наиболее популярных порно ресурсов стран снг и не только.

hosts — текстовый файл, содержащий базу данных доменных имен и используемый при их трансляции в сетевые
 адреса узлов. Запрос к этому файлу имеет приоритет перед обращением к DNS-серверам. В отличие от системы DNS,
  содержимое файла задаётся администратором компьютера. **Проще говоря: все адреса сайтов, которые вы запишите в host файл будут 
  заблокированны на вашем компьютере.**

> !!!
> ##### Если вы хотите заблокировать порно сайты на компьютере с Windows так, чтобы с разблокировкой возникли осложнения, то данный подход - ваш выбор!
> !!!

### Подробная инструкция:
1. Скопируйте все из предложенного файла
1. Откройте проводник Windows
1. Перейдите по пути C:\Windows\System32\drivers
1. В этой папке вы увидите примерно следующее:

    ![папка с host файлом](https://i.imgur.com/XHzL8q9.png)

1. Откройте свойства файла host, убедитесь, что у read only не стоит галочка:

    ![Свойства файла host](https://i.imgur.com/w3weJje.png)
1. Откройте host файл любым текстовым редактором, можно блокнотом, вы увидите следующую картину:

    ![Содержание host файла](https://i.imgur.com/WfRiuv8.png)
1. Переведите курсор на новую строку и вставьте все то, что скопировали из присета для host файла
1. Наслаждайтесь интернетом без контента для взрослых!

> Вы так же можете сделать Pull request с пополнением для нашего присета host файла, помогите нам сделать интернет чище!
>
> **Необходимо предоставить список доменов в формате 0.0.0.0 [домен сайта !без скобок!]** (после каждого домена перенос строки)
