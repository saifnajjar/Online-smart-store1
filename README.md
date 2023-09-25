


# About The Project
White-lamp is an eCommerce application built with Python Django Framework. Some of the features of this project includes custom user model, categories and products, Carts, Incrementing, Decrementing and removing car items, Unlimited Product image gallery, Orders, Payments, after-order functionalities such as reduce the quantify of sold products, send the order received email, clearing the cart, Order completion page as well as generating an invoice for the order. Also we have a Review and Rating system with the interactive rating stars that even allows you to rate a half-star rating. My account functionalities for the customer who can easily edit his profile, profile pictures, change his account password, and also manage his orders and much more.

# Setup Instructions


4. Create virtual environment `python -m venv env`
5. Activate the virtual environment `source env/Scripts/activate`
6. Install required packages to run the project `pip install -r requirements.txt`
7. Rename _.env-sample_ to _.env_
8. Fill up the environment variables:
    _Generate your own Secret key using this tool [https://djecrety.ir/](https://djecrety.ir/), copy and paste the secret key in the SECRET_KEY field._

    _Your configuration should look something like this:_
    ```sh
    SECRET_KEY=47d)n05#ei0rg4#)*@fuhc%$5+0n(t%jgxg$)!1pkegsi*l4c%
    DEBUG=True
    EMAIL_HOST=smtp.gmail.com
    EMAIL_PORT=587
    EMAIL_HOST_USER=youremailaddress@gmail.com
    EMAIL_HOST_PASSWORD=yourStrongPassword
    EMAIL_USE_TLS=True
    ```
    _Note: If you are using gmail account, make sure to [use app password](https://support.google.com/accounts/answer/185833)_
9. Create database tables
    ```sh
    python manage.py migrate
    ```
10. Create a super user
    ```sh
    python manage.py createsuperuser
    ```
    _GitBash users may have to run this to create a super user - `winpty python manage.py createsuperuser`_
11. Run server
    ```sh
    python manage.py runserver
    ```
12. Login to admin panel - (`http://127.0.0.1:8000/securelogin/`)
13. Add categories, products, add variations, register user, login, place orders and EXPLORE SO MANY FEATURES




![Screenshot 2023-08-23 025847](https://github.com/saifnajjar/Online-smart-store1/assets/76654964/7b9fb2ca-8b49-4c36-96fc-bf95dbd2f18d)
![Screenshot 2023-08-23 025914](https://github.com/saifnajjar/Online-smart-store1/assets/76654964/0cd7c653-52f8-49bc-a5b6-942e73ebe775)
![Screenshot 2023-08-23 025930](https://github.com/saifnajjar/Online-smart-store1/assets/76654964/ae5e2096-671b-48fa-880f-107d227f6c58)
![Screenshot 2023-08-23 025940](https://github.com/saifnajjar/Online-smart-store1/assets/76654964/76c4172a-113e-4108-8c7c-367c1ff4e25c)
![Screenshot 2023-08-23 030005](https://github.com/saifnajjar/Online-smart-store1/assets/76654964/333ec9f8-7c4b-4554-9d2b-b749dde6124e)
![Screenshot 2023-08-23 030017](https://github.com/saifnajjar/Online-smart-store1/assets/76654964/a9145cbc-c7d3-4202-acbf-a51c491ace9d)
![Screenshot 2023-08-23 030027](https://github.com/saifnajjar/Online-smart-store1/assets/76654964/21a34841-ac05-4008-8407-e65adf100627)

