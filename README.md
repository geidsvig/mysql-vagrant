# mysql-vagrant

mysql-vagrant is a quick way to run mysql locally for development without an ssh tunnel

### Start server

     $ vagrant up

### Connect to mysql from external:

- host: 33.33.33.1
- username: root
- password: root

### Ensure MySQL is available 

Restart MySQL if down by running:
```
sudo /etc/init.d/mysql restart
```

verify by running:
```
mysql -u root -p
```

### Warning

For development use only, do not use in production.
Also, make sure your mysql port (3306) is not open on your computer for a local network or in general.

### License

MIT
