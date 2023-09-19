# PDF-QA-webapp-langchain
Web app that lets you upload a PDF and query its content by asking questions.<br>
This web app is built using:
- LangChain
- Streamlit
- OpenAI
To use this web app:
1. Install all the dependencies using requirements.txt
2. Add your OpenAI API secret key and desired cache directory to the .env file
3. Execute the pdfapp.py file using 'streamlit run pdfapp.py'
After executing the .py file, you will receive a URL to access the web app. Upload the PDF and query its content by asking questions.<br>
Using OpenAI services (Embedding and LLM) will incur costs. OpenAI provides new accounts with $5 for usage. The costs incurred will vary depending on the models used. Costs are associated with each document uploaded and each question asked.
