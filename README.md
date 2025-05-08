# Spark notebooks quality check using Ollama LLM


1) - Install Ollama using - brew install ollama
2) - I used llama2 version . Pull llama2 version using below command -  ollama pull llama2
3) - Run using - ollama run llama2 


      ![image](https://github.com/user-attachments/assets/1b3de912-a20d-44e9-8333-215285ccc8c8)



4) - I have spark running in docker. I opened Jupiter Notebook and added below code
![image](https://github.com/user-attachments/assets/c8ca34f6-2dd4-4539-8cae-9cf7220fc262)
![image](https://github.com/user-attachments/assets/cf6936c7-dc7c-413e-8c64-c5a24f6f6f8e)

![image](https://github.com/user-attachments/assets/bff68b12-3e1d-4c61-a6af-42f3518e6a48)


Please note down few important point

![image](https://github.com/user-attachments/assets/1d28581e-446b-4915-97f6-cda37bddf709)


    # Call local Ollama API
    ollama_url = "http://host.docker.internal:11434/api/generate"  - This code is consuming ollama model running in my local mac.

Steps for running jupiter notebook in Docker is given below

1. Install Docker for Windows/ Mac in your laptop (  I am using Mac)![image](https://github.com/user-attachments/assets/3341c6a5-d943-4110-800c-d2bb9552d23f)

2.  I have provided docker-compose file in repository ![image](https://github.com/user-attachments/assets/3d051724-af75-451d-815f-bcf53cbbcd91)
3.  In prompt execute command -  docker-compose up -d ![image](https://github.com/user-attachments/assets/d643eb7e-3bf6-4a4e-a0c4-ab616920de81)
4.  You will see ![image](https://github.com/user-attachments/assets/d5861e89-cc01-44f8-bdba-c25e72fcc467)
5.  Open http://localhost:8888/ , you will get Jupyter notebook in browser
6.  It will ask you enter a token to create password ![image](https://github.com/user-attachments/assets/bb77d853-1eb8-4ce7-acb9-a608b3dae8fe)
7.  You can get token from the below section - refer query string- ![image](https://github.com/user-attachments/assets/f6b4348c-6b2f-40e4-b4eb-80e0b3898f48)
8.  Once you logged in , you can upload notebook in the interface and test above scenarios

 


