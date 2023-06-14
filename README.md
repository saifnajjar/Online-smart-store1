# grade_project
this is grade project for my university

White-lamp is an eCommerce application built with Python Django Framework. Some of the features of this project includes custom user model, categories and products, Carts, Incrementing, Decrementing and removing car items, Unlimited Product image gallery, Orders, Payments, after-order functionalities such as reduce the quantify of sold products, send the order received email, clearing the cart, Order completion page as well as generating an invoice for the order. Also we have a Review and Rating system with the interactive rating stars that even allows you to rate a half-star rating. My account functionalities for the customer who can easily edit his profile, profile pictures, change his account password, and also manage his orders and much more.

Setup Instructions
Clone the repository git clone https://github.com/yahyakmail59/grade_project.git

Navigrate to the working directory cd grade_project

Open the project from the code editor code . or atom .

Create virtual environment python -m venv env

Activate the virtual environment source env/Scripts/activate

Install required packages to run the project pip install -r requirements.txt

Rename .env-sample to .env

Fill up the environment variables: Generate your own Secret key using this tool https://djecrety.ir/, copy and paste the secret key in the SECRET_KEY field.

Your configuration should look something like this:

SECRET_KEY=47d)n05#ei0rg4#)*@fuhc%$5+0n(t%jgxg$)!1pkegsi*l4c%
DEBUG=True
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_HOST_USER=youremailaddress@gmail.com
EMAIL_HOST_PASSWORD=yourStrongPassword
EMAIL_USE_TLS=True
Note: If you are using gmail account, make sure to use app password

Create database tables

python manage.py migrate
Create a super user

python manage.py createsuperuser
GitBash users may have to run this to create a super user - winpty python manage.py createsuperuser

Run server

python manage.py runserver
Login to admin panel - (http://127.0.0.1:8000/securelogin/)

Add categories, products, add variations, register user, login, place orders and EXPLORE SO MANY FEATURES
