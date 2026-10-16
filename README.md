a simple chatbot that runs in your teminal using hugginfacehub api token 
<br>
1.Create a .env file in the working directory
<br>
2.paste your huggingface hub api token--> HUGGINGFACEHUB_API_TOKEN='your_api_token' 
<br>
you can also choose your preferred model by editing the repo_id in llm=HuggingFaceEndpoint(repo_id='openai/gpt-oss-120b', task='text-generation', ) at line 7 and pasting the repo_id of the model of your choice
