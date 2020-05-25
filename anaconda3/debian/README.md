
 ```bash
 docker build -t anaconda3ssh/anaconda3ssh .

docker run -i -t anaconda3ssh/anaconda3ssh /bin/bash

docker rm $(docker ps --filter "status=exited" -q)



```

```bash
docker run `
--rm `
--name anaconda3ssh `
-i `
-p 12222:22 `
-t anaconda3ssh/anaconda3ssh `
/bin/bash
```