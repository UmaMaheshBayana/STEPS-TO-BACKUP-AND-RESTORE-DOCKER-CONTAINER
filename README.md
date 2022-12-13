# STEPS-TO-BACKUP-AND-RESTORE-DOCKER-CONTAINER

****Use the below commands to take docker container backup****
```
docker commit -p $CONATINER_ID $BACKUP_NAME
````
```
docker save -o $file.tar $BACKUP_NAME
````

****Use the below commands to restore the backups****

```
sudo docker load -i $my-backup.tar
````

```
docker images
````

```
sudo docker run -it $dockerimage
````
