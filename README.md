# Docker Project

Project for the **Dockerfiles** and **Docker Compose** sections

## Initial configuration

- Create account at the https://unsplash.com
- At the https://unsplash.com/oauth/applications create new **demo** application with title **"Images Gallery"**.
  Demo applications are limited to 50 requests per hour
- In the newly created application find section **"Keys"** and copy **Access Key**
- In the **api** folder create file **.env.local** and add there following line:

```
UNSPLASH_KEY=xTcbt_swPxmA32VRLCKoIAoYoC9KWDVb69GmKEBqHVg

Secret Key=C6evjsBnCSJZ4xMdz2PslWddaxKx2DEuE1Dhlk8YDtM

Application Id=527416
```

**EXAMPLE** with fake code(don't try to use it in your app):

```
UNSPLASH_KEY=2MJvApIkV13hfg2LmQlneILfHoJ2ttlzSdPKefGOyKM
```

- Save modified **.env.local** file
