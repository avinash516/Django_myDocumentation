# Django_myDocumentation   ......> By Satheesh Matampalli
## Django Introduction :

* **Python web Frameworks :**
  * Django
  * Flask
  * web2py
  * Bottle
  * cherrypy
  * etc.....
### What is a web Framework?
 * **A web framework or web application framework is a software framework that is designed to support the development of web applications including web services, web resources, and web APIs. Web frameworks provide a standard way to build and deploy web applications.**
 
### Why django Framework?
 * **Django is a Python web framework**
 * **A Framework provides a structure and common methods to make the life of a web application developer much easier for building    flexible, scalable and maintainable web applications.**

### What is Django ?

* **A Python web framework is a code library that provide tools and libraties to simplify common web development operations.**
* **It is based on MVT (Model View Template) design pattern.**
* **Django is a high-level and has MVC,MVT styled Architecture.**
* **Django web framework is written on quick and powerful python language.**
* **Django has a open-source collection of libraries for building afully functioning web application.**
* **It takes less time to build application after collecting client requirement.**

### Features of Django :

 * **very fast  :**
   * **It works very fast.**
 * **Fully Loaded  :**
   * **Django includes various helping task modules and libraries which can be used to handle common Web development tasks. Django takes care of user authentication, content administration, site maps.**
 * **Secure  :**
   * **Its user authentication system provides a secure way to manage user accounts and passwords.**
 * **Scalable  :**
   * **Django is scalable in nature and has ability to quickly and flexibly switch from small to large scale application project.**
* **OpenSource  :**
  * **Django is versatile in nature which allows it to build applications for different-different domains.**
  

### MVT Architecture of Django  :

* **Every Web applications follows architectures**
  * **MVC (Model View Controller)**
  * **MVT (Model View Template)**
  * **etc..**
* Django is a MVT pattern.
* MVC is slightly different from MVT as Django itself takes care of the Controller part.
<img src='mvc.PNG' alt='mvc' />

<img src='mvt1.PNG' alt='mvc' />



* **MVT is a software Design patern**
* **It is a collection of three important components Model View and Template.**
* **Model  :**
  * **The Model helps to handle database. It is a data access layer which handles the data.**
* **Template  :**
  * **The Template is a presentation layer which handles User Interface part completely.**
* **View  :**
  * **The View is used to execute the business logic and interact with a model to carry data and renders a template.**

<img src='mvt.png' alt='mvt' />
  
* **Here, a user requests for a resource to the Django, Django works as a controller and check to the available resource in URL.If URL maps, a view is called that interact with model and template, it renders a template.Django responds back to the user and sends a template as a response.**

## **Django Installation :**
  * **1. download python from website.**
  * **2. set all path for python and scripts.**
  * **3. heck wheather 'pip' is working or not in the 'cmd'**
  * **4. install django # # (latest Version 2.0) wait for installation**
      `pip install Django==2.0.1"` or `pip install django`
  * **5.After installing to check the version of Django Framework.**
    ```
       cmd>django-admin --version
                 (or)
       cmd>python
       >>>import django
       >>>django.get_version()    or    django.VERSION
          '1.11'                   (1,11,0, 'final',1)```

