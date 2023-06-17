# E-GUIDANCE-HUB
mern-ecommerce
Frontend-> React JS Backend-> Node JS & Express JS Database-> MongoDB
npm install
install frontend packages
cd client
npm install

sample code for backend .env
MONGODB_URI=YOUR_MONGODB_URI
JWT_SECRET=YOUR_JWT_SECRET
BRAINTREE_MERCHANT_ID=YOUR_BRAINTREE_MERCHANT_ID
BRAINTREE_PUBLIC_KEY=YOUR_BRAINTREE_PUBLIC_KEY
BRAINTREE_PRIVATE_KEY=YOUR_BRAINTREE_PRIVATE_KEY
create another .env file inside client directory for REACT_APP_API_URL.
cd mern-ecommerce/client
sudo nano .env
sample code for frontend .env
REACT_APP_API_URL=YOUR_API_URL
Instructions:
for mongodb atlas database creation follow this tutorial-
https://www.youtube.com/watch?v=KKyag6t98g8

you can use any random string as JWTSECRET
for localhost REACT_APP_API_URL is http://localhost:5000/api but for heroku (server deployment) it will be different
note: add .env on .gitignore
for server deployment use secrets directly
deploy this project on your local server by using this command
cd mern-ecommerce
npm run dev
note: both backend & frontend server will start at once 
