#build container using the following command
#tag can be replaced with any other tag; use your username

$ docker build . -t zereneh/cn8822-web 

# run it; change name and image name accordingly

$ docker run -d -p80:8080 --name cn8822-web zereneh/cn8822-web
