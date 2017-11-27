# My Public IP app

## dockerising a PHP app with nginx and PHP

```
├── code
│   └── index.php
├── docker-compose.yml
├── README.md
└── site.conf
```

**NOTE:**
- the expose port is defined in `docker-compose.yml`. In this example I used th 8080
- in `site.conf` is important to set you correct `server_name`. In this example I used `myip_docker.local` (update your hosts file)

---

 So you can clone this repository, and if you have docker and docker-compose correctly installed, you can give a `docker-compose up` in the root of the repository and then go on [http://myip_docker.local:8080/](http://myip_docker.local:8080/)