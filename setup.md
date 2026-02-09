# n8n local setup using Docker
```
docker volume create n8n_data
docker pull n8nio/n8n   
docker run -it --rm \                                                                    1 ↵
-p 5678:5678 \
-v n8n_data:/home/node/.n8n \
n8nio/n8n
```
Expected Output :
```
Editor is now accessible via:
http://localhost:5678
```
