# run a postgres db using a data directory
`docker run -v ~/nrs/var/lib/postresql-metabase/:/var/lib/postgresql/data -it postgres:11.1-alpine`
# find the container id
`docker container ls`
# get a terminal prompt inside the container and run psql etc inside it
`docker exec -it <CONTAINER_ID BLABLABLABLA> /bin/bash`
