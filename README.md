# simplilearn-phpinfo
[![ci](https://github.com/Chironx-ps1/simplilearn-phpinfo/actions/workflows/ci.yaml/badge.svg?branch=2021-06)](https://github.com/Chironx-ps1/simplilearn-phpinfo/actions/workflows/ci.yaml)
```bash
docker container run --detach --entrypoint php --name php-latest --publish 80:8080 --rm --workdir /src index.docker.io/suvojitchironx/simplilearn-phpinfo-2021-06:latest -f index.php -S 0.0.0.0:8080
```
