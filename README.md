### How to run

```bash
docker build -t my_image .
docker run -it --user [username] --network=host --ipc=host -v $PWD/src:/src --privileged my_image
```
### Reference
https://www.youtube.com/watch?v=XcJzOYe3E6M