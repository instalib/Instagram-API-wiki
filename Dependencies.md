**PHP >= 5.6 is required**

**Dependencies:**

`gd, curl, ffmpeg, ffprobe, mbstring and exif`

External info. for **Windows** users: http://php.net/manual/en/install.windows.extensions.php

For **OS X** users (using ports):
```
sudo port install php56-gd
sudo port install php56-curl
...
```

For **Linux** users:
```
sudo apt-get install php5-gd
...
```

## Composer

You can install it using composer:

```
composer require mgp25/instagram-php
```

or if you want latest commits (at your own risk): 

```
composer require mgp25/instagram-php dev-master
```

## Dockerfile

Dockerfile available: https://github.com/mgp25/Instagram-API/blob/master/Dockerfile