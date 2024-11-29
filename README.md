$ cd Frontend
$ npm install (to install frontend-side dependencies)
$ npm run start (to start the frontend)

- cd Backend and Set environment variables in config.env under ./config
- Create your mongoDB connection url, which you'll use as your MONGO_URI
- Supply the following credentials
  ##inside config file
  NODE_ENV = development
  PORT =5000
  URI =http://localhost:3000
  MONGO_URI = "mongodb://admin:password@localhost:27017"
  JWT_SECRET_KEY = "secret"
  JWT_EXPIRE = 60m
  RESET_PASSWORD_EXPIRE = 3600000

SMTP_HOST =smtp.gmail.com
SMTP_PORT =587
EMAIL_USERNAME = example@gmail.com
EMAIL_PASS = your_password

$ npm install (to install backend-side dependencies)
$ npm start (to start the backend)
