# Sam-Thing Garden Ecommerce

**REQUIREMENTS**
- Python installed recommended=3.10.7. 

**Download Source Code**
```
https://github.com/vincentrondero/Sam-Thing.git
```

**Create virtual environment**
```
py -m venv venv
```
**Make sure you activate your virtual environment**
```
venv\Scripts\activate
```
**Execute Following Commands:**
```
pip install django==3.0.5
pip install django-widget-tweaks
pip install xhtml2pdf
```
Or
```
pip install -r requirements.txt
```
**Then Execute Following Commands:**
```
py manage.py makemigrations
py manage.py migrate
```
**First admin will login ( for username/password run following command)**
```
py manage.py createsuperuser
```
- Give username, email, password and your admin account will be created.
- This will allow the administrator to add products and navigate the dashboard
- **In the static/product_image folder a sample image can be used to add products for testing.**

**Then runserver**
```
py manage.py runserver
```

**Now enter following URL in Your Browser**
```
http://127.0.0.1:8000/
```




Sir hindi po kami malakas magprogram
