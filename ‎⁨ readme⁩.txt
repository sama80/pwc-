
1. Extract the ZIP File: 
    - Extract the contents of the ZIP file to a directory of your choice.

2. Set Up the Virtual Environment:
   
    cd path/to/llm_evaluator
    python -m venv venv
    
3. Activate the Virtual Environment:
    - Windows:
     
      venv\Scripts\activate
  
    - macOS/Linux:
     
      source venv/bin/activate
   

4. nstall the Dependencies:
   
    pip install -r requirements.txt
 

5. Run the Web Scraping Script:
   
    python scrape.py
   
    - This script will scrape the provided website and store the data in the Pinecone vector database.

6. Start the Flask Application:
   
    python app.py
    
7. Access the Application:
    - Open your web browser and go to `http://127.0.0.1:5000/` to interact with the web application.


