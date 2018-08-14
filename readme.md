## What is this?

project from taken course Learn Node - Dang Thats Delicious from Wes Bos

## How to Run

Define a `variables.env` in you project with the following settings:

```
ODE_ENV=development
DATABASE=`mongodb connectionstring`
MAIL_USER=
MAIL_PASS=
MAIL_HOST=
MAIL_PORT=
PORT=
MAP_KEY=`google maps key`
SECRET=
KEY=
```

```bash
#Start server on localhost
npm start


# Populate data and run application
npm run sample

#If you have previously loaded in this data, you can wipe your database 100% clean with:
npm run blowitallaway
```

That will populate 16 stores with 3 authors and 41 reviews. The logins for the authors are as follows:

| Name          | Email (login)      | Password |
| ------------- | ------------------ | -------- |
| Wes Bos       | wes@example.com    | wes      |
| Debbie Downer | debbie@example.com | debbie   |
| Beau          | beau@example.com   | beau     |
