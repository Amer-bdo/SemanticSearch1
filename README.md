# SemanticSearch1

This is a prototype Web Application demonstrating the capablity to perform semantic search of multiple PDF documents and pass the text chunks to GPT3 for question answering.
The user story being addressed is - 
"As a Auditor, I want to ask specific questions relating to Auditing standards as documented by the FRC. I want a fast and scalable solution that can manage 1000+ pages of text acr
multiple documents and I want to leverage the AI capabilities of GPT3 without the downside of hallucinations."

This project was developed in Python3 using the MS VS Code IDE running on Windows 10.
The tech stack uses
- The OpenAI GPT 3.5 turbo API
- Pinecone vector database
- Open source Embeddings 
- Streamlit for the App deployment and hosting

## Installation

1. Register with OpenAI and acquire an API licence key
2. Register with app.pinecone.io and acquire a licence key
2.1 Create an index in the pinecone vector database to hold the document embeddings, set the dimensions to the value specifies in teh embeddings API (384)
3. Register with streamlit to host the app
4. Within the streamlit app registration, reference the github repo name, branch and main file path
5. Within the streamlit app settings add the secrets for the OPENAI_API and PINECONE_API keys

## Usage

https://amer328-semanticsearch1-main-noxfw4.streamlit.app

Use radio button to either add new document embeddings to the Pinecone database or perform semantic search


## Contributing

N/A

## License

N/A
