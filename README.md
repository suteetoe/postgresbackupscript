# Auto backup script

1.Create target folder backup

```
$ mkdir /home/posrgres-backup
$ chmod 777 /home/postgres-backup
```

2.Switch to user postgres
```
$ su - postgres
```

3.Create script file

```
$ wget https://raw.githubusercontent.com/suteetoe/postgresbackupscript/master/backup.sh
```

4.Run backup file
```
$ bash backup.sh
```