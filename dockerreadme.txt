#Open Powershell on this Folder
docker build . -t cxjenkins
docker run -p 8081:8080 -p 50000:50000 cxjenkins