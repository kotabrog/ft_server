# ft_server

## Overview

I created a Docker file that can build an environment for nginx, mysql, and wordpress.

## Requirement

- Ubuntu
- Docker 19.03.6

## Usage

```
git clone ...
cd ft_server
docker build -t test .
docker run -d -p 8080:80 -p 443:443 test
```

You can get started with nginx by accessing the URL: https://127.0.0.1/

## Features

- Access to nginx: https://127.0.0.1/
- Access to wordpress: https://127.0.0.1/wordpress/
- Access to phpmyadmin: https://127.0.0.1/phpmyadmin/
- Redirect to https: http://127.0.0.1:8080/

## Author

[twitter](https://twitter.com/Kotabrog)

## Licence

[MIT](https://github.com/kotabrog/ft_server/blob/main/LICENSE)