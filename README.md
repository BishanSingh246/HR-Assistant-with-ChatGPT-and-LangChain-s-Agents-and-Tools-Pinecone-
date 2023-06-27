<h1 align="center">
    <b>HR Assistant with ChatGPT and LangChain’s Agents and Tools (Pinecone)</b> 
<br>
</h1>

## Description
In this repository, we are currently using code provided in referenced blog and checking if the code works as expected, just like how it was described in the blog post.

<br>

Reference - <a href='https://pub.towardsai.net/creating-a-mostly-autonomous-hr-assistant-with-chatgpt-and-langchains-agents-and-tools-1cdda0aa70ef'>Creating a (mostly) Autonomous HR Assistant with ChatGPT and LangChain’s Agents and Tools</a>

## Instruction
To use this repository, follow these steps:

1. Set it up on your local machine.

2. Install all dependencies using the following command ```pip install -r requirements.txt```.

3. Generate Api key from <a href='https://platform.openai.com/account/api-keys'>OpenAI</a>. 

4. Copy and paste your OpenAI API key in ```app.py```  file line number 24 and in ```store_embeddings_in_pinecone.ipynb``` file in 4th code block.

5. Create account in <a href='https://www.pinecone.io/'>Pinecone</a>. 

6. Copy your Pinecone API key and Environment and past it in ```app.py```  file line number 27 and in ```store_embeddings_in_pinecone.ipynb``` file in 6th code block.
 
## Running the Application
To run the application:

1. Run ```store_embeddings_in_pinecone.ipynb``` file first. You can execute each code block individually or you can choose to run all the code blocks together in one go.

2. Open a terminal and type ```streamlit run main.py``` then press enter

