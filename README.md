# wikipedia_api

# Instructions:

1. Navigate to the Project Directory:
cd wikipedia_api

2. Install Dependencies:
pip install -r requirements.txt

3. Apply Database Migrations:
python manage.py migrate

4. Run the Development Server using:
    . python manage.py runserver

   
   or
    . curl "http://127.0.0.1:8000/search_wikipedia/?search_term=rum&language=cs"

   
    . curl "http://127.0.0.1:8000/search_wikipedia/?search_term=rumbellion&language=cs"

   
    . curl "http://127.0.0.1:8000/search_wikipedia/?search_term=abcdefgh&language=cs"

   
    . curl "http://127.0.0.1:8000/search_wikipedia/?search_term=abcd&language=cs" ..

   
   (Just change the search_term and the language)

# Access the API
