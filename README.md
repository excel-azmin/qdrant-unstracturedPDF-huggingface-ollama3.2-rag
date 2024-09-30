# Local Installation 

* Install ollama 
```
curl -fsSL https://ollama.com/install.sh | sh
```

* If you are on Windows | macOS follow [this](https://ollama.com/download)

* Download `ollama3.2` Model
```
ollama run llama3.2
```
* Clone the repo
```
git clone https://github.com/excel-azmin/qdrant-unstracturedPDF-huggingface-ollama3.2-rag.git
```
* Enter the project Directory
```
cd qdrant-unstracturedPDF-huggingface-ollama3.2-rag
```
* Run `qdrant` Vector Database
```
docker-compose up
```
* If you don't have docker [Install Docker](https://docs.docker.com/engine/install/)
* Install the dependencies
```
pip install -r requirements.txt
```
* Run the Application
```
streamlit run app.py
```    
* Enjoy the Appp [http://localhost:8501/](http://localhost:8501/)


![image](https://github.com/user-attachments/assets/f2f21eed-2f5e-4fde-a221-7777dd469e3c)


