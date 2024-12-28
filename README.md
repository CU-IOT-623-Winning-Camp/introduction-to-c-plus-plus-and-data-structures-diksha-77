
<div align="center">
 <strong><h1>Indian Road Safety 🚥</h1></strong>
  <strong><h3>Road Condition Analyser (RCA) 📊</h3> 
  <i>"A step to ensure safe road journey"</i></strong>
</div>

<br>

### Install For Development ⚡:

* Run these commands in order:

```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
cd webapp/
python manage.py migrate
python manage.py runserver
```

* After this go to http://localhost:8000/ to see the running app in development.
* To detect road damage use the api provided at this endpoint http://localhost:8000/api/road/

### Indian Roads Images Dataset 💾:

- These images are provided in __Dataset for GRDDC 2020__ which consists of Indian road images.

### Tech Stack That We Used 👨‍💻:

1. Tensorflow
2. Numpy
3. Open-CV
4. Django
5. Django Rest Framework
6. SQL
7. Google Maps API
