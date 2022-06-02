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
    $ git clone git@github.com:danieljfar/siclo-challange.git
    ```

2. Run Django
    The following command must be run inside the virtual environment 
    ```bash
    $ python manage.py runserver
    ```
3. Run Vue
    ```bash
    $ npm install
    ```
    ```bash
    $ npm run serve
    ```
4. Necessary substitutions for Stripe:
  - a. frontend:
    
      Inside the views folder in the Checkout.vue file you must add your Stripe Public Key that you will find in your stripe profile after registering
    
  - b. backend:
    
      Inside the djackets_django project folder in the settings.py file you must add your Stripe Secret Key that you can find in your stripe profile after registering
    
5. To go to:
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
