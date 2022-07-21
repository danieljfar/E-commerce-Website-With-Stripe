# E-commerce Website Using Stripe

## Technologies
- Backend:
    - Django Rest Framework
- Frontend:
    - Vue

## Requirements
- [Git](http://git-scm.com/)
- [Vue](https://vuejs.org/)
- [Python](http://www.python.org/)

## Setup
1. Clone repo

    ```bash
    $ git clone git@github.com:danieljfar/E-commerce-Website-With-Stripe.git
    ```
    
2. Install Backend Requirements -
    The following command must be run inside the virtual environment 
    
    ```bash
    $ pip install -r requirements.txt
    ```
    
3. Run Django

    ```bash
    $ python manage.py runserver
    ```
    
4. Install Frontend Dependencies

    ```bash
    $ npm install
    ```
    
4. Run Vue

    ```bash
    $ npm run serve
    ```
    
5. Necessary substitutions for Stripe:
  - a. frontend:
    
      Inside the views folder in the Checkout.vue file you must add your Stripe Public Key that you will find in your stripe profile after registering
    
  - b. backend:
    
      Inside the djackets_django project folder in the settings.py file you must add your Stripe Secret Key that you can find in your stripe profile after registering
    
## To go to:
  - a. frontend:
    ```
      http://localhost:8080/
    ```
  - b. backend:
    ```
      http://localhost:8000/
    ```
  - c. backend admin:
    ```
      http://localhost:8000/admin
    ```
