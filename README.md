# docker-stackedit
dockerfile for stackedit

# Useage

Change the base image in the Dockerfile.
Example `From ubuntu:14.04`

Build your image:

```
docker build -t aplusplus/stackedit .
```

Run your container:

```
docker run -d -p 3000:3000 aplusplus/stackedit
```

You can also see [my blog](http://njuaplusplus.com/post/dockerize-stackedit/).
