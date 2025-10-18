


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
13. Add categories, products, add variations, register user, login, place orders and EXPLORE SO MANY FEATURES<img width="942" height="857" alt="Screenshot 2023-08-23 025847" src="https://github.com/user-attachments/assets/3ddec8fd-6458-4206-bd84-8a3aa00fcca3" />
<img width="917" height="482" alt="Screenshot 2023-08-23 025914" src="https://github.com/user-attachments/assets/2e36a94d-3ab8-410d-8678-79cf8eab85a4" />
<img width="987" height="752" alt="Screenshot 2023-08-23 025930" src="https://github.com/user-attachments/assets/67903426-7cf9-4fa5-adcc-820f1eb98fd8" />


<img width="946" height="637" alt="Screenshot 2023-08-23 025940" src="https://github.com/user-attachments/assets/c689eaa4-bc6b-422c-b6cb-3941aba82d0c" />




<img width="925" height="402" alt="Screenshot 2023-08-23 030005" src="https://github.com/user-attachments/assets/7030d0db-5cbf-4ad1-822a-b581e4394ac3" />

