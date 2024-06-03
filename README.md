docker build -t uvg-chat-image .
docker run --name chat-container -p 8080:80 uvg-chat-image
docker start chat-container   


docker stop chat-container
docker rm chat-container
docker rmi uvg-chat-image