Астер на ubuntu
При установке asterisk с нуля необходимо:

1. Выбрать корректную ссылку для дравера odbc для MariaDB, прописать ее в переменную в playbook {dbc_src_url} - https://mariadb.com/downloads/connectors/connectors-data-access/odbc-connector/
2. Выбрать версию asterisk  прописать ее в переменную в playbook { asterisk_version }  - 20-current 