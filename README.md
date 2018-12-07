# molecule-test


#Dependencies
docker
docker-py


molecule --debug test


molecule test --destroy=never
docker exec -it instance /bin/bash

