### How to run

```bash
docker build -t my_image .
docker run -it --user [username] --network=host --ipc=host -v $PWD/ros_ws:/ros_ws --privileged my_image
```

### Troubleshooting

If run in docker file causes error, (format exec error), then install:

```bash
sudo apt install qemu-user-static
```

### Reference

https://www.youtube.com/watch?v=XcJzOYe3E6M
