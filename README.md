# Spark notebooks quality check using Ollama LLM

1) - Install Ollama using - brew install ollama
2) - I used llama2 version . Pull llama2 version using below command -  ollama pull llama2
3) - Run using - ollama run llama2 


  ![image](https://github.com/user-attachments/assets/1b3de912-a20d-44e9-8333-215285ccc8c8)

  
4) - I have spark running in docker. I opened Jupiter Notebook and added below code
![image](https://github.com/user-attachments/assets/c8ca34f6-2dd4-4539-8cae-9cf7220fc262)
![image](https://github.com/user-attachments/assets/cf6936c7-dc7c-413e-8c64-c5a24f6f6f8e)

![image](https://github.com/user-attachments/assets/bff68b12-3e1d-4c61-a6af-42f3518e6a48)


Please note down few important things

![image](https://github.com/user-attachments/assets/1d28581e-446b-4915-97f6-cda37bddf709)


    # Call local Ollama API
    ollama_url = "http://host.docker.internal:11434/api/generate"  - This code is consuming ollama model running in my local mac.
