# Assignment #1

## Find our container Images
3. Search for Ubuntu bases images:
```sh
docker search ubuntu
```
> Note: Read about how to use more advanced search options [here](https://docs.docker.com/engine/reference/commandline/search/)

4. Fetch the image from the public registry 
```sh
docker pull ubuntu:latest
```
> QUESTION: What does Latest mean? Can you replace that with something else?

5. List all the images in the local host registry – 
```sh
docker images
```

6. Search for Ubuntu base images – 
```sh
docker search ubuntu
```

7. Fetch a spsific version of an image from the public registry –
```sh
 docker pull ubuntu:xenial
 ```

8. List all the images in the local host registry – 
```sh
docker images
```

9. Try pulling a different version of ubuntu –
```sh
docker pull ubuntu:<version>
```
[Next: **Run our container** ➡️](assignment-3.md)