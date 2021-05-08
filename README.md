# PLD_SMART - **Lowympact** - *References*

## Introduction to the subject

Final proposition from the 10/03/2021

> https://drive.google.com/file/d/173HtS0QquKTjBxa0D0jQqoLsgOkNAKeB/view?usp=sharing

## Commercial video

> https://drive.google.com/file/d/1TS-zcjohSiBu4trno0XB8PVEWYCX8QMU/view?usp=sharing

## Features

General description of the differents features

> https://hackmd.io/@hexaone/Bk4a8tC8d

## Installation / Using our application

So as to use our application, you can simply go to https://lowympact.fr (preferably on your phone to have an optimal display). From here, you can use the application from your browser or install it on your phone by going to the settings of your browser (it's a Progressive Web App). You can also use our API : the documentation is located on https://api.lowympact.fr/api-docs

## Repositories

### REFERENCES

Link to our GitHub repository

> https://github.com/Lowympact/lowympact

### FRONT-END

Link to our GitHub repository

> https://github.com/Lowympact/lowympact-front

Installation process is quite simple : run `git clone` and `npm install` into repository's folder. Use `npm start` to start development server at `http://localhost:3000/`.

### BACK-END

Link to our GitHub repository

> https://github.com/Lowympact/lowympact-back

Installation process is quite simple : run `git clone` and `npm install` into repository's folder. Use `npm run dev` to start development server at `http://localhost:8080/`. If you want a production deployment just hit `npm start`. Do not forget to create your `.env` file with secrets into repository's folder.

Swagger exposition is available at `http://localhost:8080/api-docs/`

You would need the following .env file at the root of the back-end folder. In any case, GOOGLE_API_KEY is in restricted usage (accept requests coming from https://api.lowympact.fr/ only) and won't works in local : 
```
PORT=8080
MODE="development"

MONGODBPWD="a2tLQrNuOhXk7eZg"
MONGO_URI="mongodb+srv://lowympactBack:a2tLQrNuOhXk7eZg@cluster0.sx8sg.mongodb.net/lowympact?retryWrites=true&w=majority"

LOCAL_NODE="http://localhost:7545"

LOWYMPACTAPI_KEY="99d8fb95-abdd-4885-bf6c-3a81d8874043"

GOOGLEAPI_KEY="AIzaSyBANw2u7J088INq1DrMS-dp9bLoYG41v7c"

JWT_SECRET=dafegqaswiyasdg
JWT_EXPIRE=30d
```

### BLOCKCHAIN

Link to our GitHub repository

> https://github.com/Lowympact/lowympact-blockchain

Installation process is quite simple : run `git clone` and `npm install` into repository's folder. Moreover, you'll need to install *[Ganache](https://www.trufflesuite.com/ganache)*

## Stack

MERN (MongoDB, Express, React, NodeJS) x Solidity

## VPS

### FRONT-END

Located on Corentin's Virtual Private Server : 
> https://lowympact.fr/

### BACK-END

Located on Thibaut's Virtual Private Server : 
> https://api.lowympact.fr/


## Graphic chart

You can find the first models we made [here](https://drive.google.com/file/d/1tVLzX_o6eVDfy2V_gtjAe8ZO2xQjHl8H/view?usp=sharing).

Our idea was to design a minimalist and easy to use application.

## Sources

Following are some sources that helped us during our work
- [Coton's traceability](https://github.com/solenebutruille/Blockchain_Cotton_Tracabilite)
- [CO2 footprint compute](https://www.co2nnect.org/help_sheets/?op_id=602&opt_id=98)
