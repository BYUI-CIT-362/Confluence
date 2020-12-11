#Confluence
This is just a generic Confluence container that was created for kubernetes. To run locally:

`docker build . -t confluence`
`docker run -p 8090:8090 --memory="6g" confluence`