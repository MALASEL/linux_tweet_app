# Linux Tweet App

This is a simple NGINX website that allows a user to send a tweet. 

To use it:

1) Build it using the below command :
`docker build -t linux_tweet_app .`

2) Run it using the below command:
`docker container run --detach -p 8081:80 linux_tweet_app`
or
`docker run -d -p 8081:80 dee24109faea`
where dee24109faea is the container-image.

