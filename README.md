# Lab04app

Instrukcja uruchomienia
Lokalnie
   python -m venv venv
   source venv/bin/activate  
   pip install -r requirements.txt
   python app.py

Docker
   docker build -t my_doc .
   docker run -p 8080:8080 my_doc

Docker Compose
   docker-compose up 
  
