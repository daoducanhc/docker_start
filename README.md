##### Docker Desktop - easy to use
!!! Only support ubuntu 21, 22

---

##### So, use Docker Engine instead
[Installation](https://docs.docker.com/engine/install/ubuntu/)

---

##### Add user so we no need to sudo every time we call ```docker```

```
sudo groupadd docker
sudo usermod -aG docker $USER
newgrp docker
```

##### Test
```
docker run hello-world
```

---

[Start Docker with OS](https://docs.docker.com/engine/install/linux-postinstall/#configure-docker-to-start-on-boot)
