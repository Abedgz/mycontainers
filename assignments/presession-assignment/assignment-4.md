# Assignment #1

## Container names and information

16. Let's get some information about our container 
```sh
docker inspect [container_id/name]
```
> QUESTION: What can we find here? read more [here](https://docs.docker.com/engine/reference/commandline/inspect/)

17. By default Docker names our containers in a word1_word2 random pattern

    • We can give our containers a name using the `--name` parameter

    • We can also rename a running container’s name
```sh
docker rename [container_id/name] [container_new_name]
```

[Next: **Changing our containers ** ➡️](assignment-5.md)
