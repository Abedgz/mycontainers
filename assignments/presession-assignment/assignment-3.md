# Assignment #1

## Running our containers

10. Now run the container 
```sh
docker run -i -t ubuntu:xenial /bin/bash
```
> QUESTION: Read about the `-i` and `-t` options [here](https://docs.docker.com/engine/reference/commandline/run/). Why are we using these options?.

11. Exit the container.

12. List all running containers:
```sh
docker ps
```
> QUESTION: Why is our ubuntu container not running?

13. Let's restart our container
```sh
docker restart [container_name/id]
```
> QUESTION: Why are we not attached to the container?

14. List all running containers
> QUESTION: Is our container still running?

15. Let's attach to our container
```sh
docker attach [container_id/name]
```
> QUESTION: What happens once we exit the container?

[Next: **Container names and information ** ➡️](assignment-4.md)
