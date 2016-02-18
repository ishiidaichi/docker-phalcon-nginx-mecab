# docker-phalcon-nginx-mecab
Japanese natural Language processor 'Mecab' added into docker-phalcon-nginx image.

just run :

```
#pull an image
docker pull ishiidaichi/docker-phalcon-nginx-mecab

# run your Phalcon PHP app!
docker run -d -p 80:80 -v /path/to/your/app:/var/www/html ishiidaichi/docker-phalcon-nginx-mecab
```

That's it!
