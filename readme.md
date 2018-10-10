#### Simple Node.js Hello World web app
-------
To start the app run
```
npm install 
npm start
```

The server will start at http://127.0.0.1:8081/

### To use Docker

```s
$ sudo yum install -y docker #This command is to install docker on linux, use something equivalent like brew for other OS  
$ sudo systemctl start docker
$ sudo docker info
$ sudo docker build -t hello-world .
$ sudo docker run -p 8081:8081 -d hello-world
```

The server will start in the same url as mentioned above
