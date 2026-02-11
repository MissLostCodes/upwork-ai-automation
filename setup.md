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
# Workflow 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/37f71f4a-a571-4ba7-9247-e0ebef82e125" />

# Apify token setup and actor renting 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/36eb79be-cb04-46c7-b6c4-65ea9555986f" />

# Replace open ai with gemini to use free
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cc7096f6-bf48-493e-b575-6e2ef4fd4d67" />

# Gemini Response
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ff3c156f-8939-4e1a-94a0-b918ed736224" />

# Slack Message triggers for high prioroty jobs and rate limit handling updates
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8c76c76b-61d4-4423-9a5e-4d0006f77e12" />


