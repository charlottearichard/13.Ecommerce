# 13.Ecommerce [COMPLETED ✅] 


## Game Plan 

1. Set up project: Set up repo, identify issues. 
2. Scaffold application's architecture: Install npm packages. 
3. Create models (category, product, tag, productTag). 
4. Create routes. 
5. Test routes with insomnia. 

## Tasks 
- [x] Install npm packages (mysql2, sequelize, dotenv) 

- [x] Connect schema to database:

    - [x] put sql password and username in .env file (this is conected to 'connection.js')
    - [x] .gitignore env file 
    - [x] mysql -u root -p (log-in w/ password)
    - [x] source db/schema.sql
    - [x] show databases; (to check if datbase has be successfully created)
    - [x] use ecommerce_db; (to change into this database)

- [x] Define 'Category' columns 

- [x] Define 'Product' columns 

- [x] Define 'Tag' columns 

- [x] Define 'ProductTag' columns

- [x] Create Product routes

- [x] Create Category routes

- [x] Create Tag routes 

- [x] Connect seeds to database. 

- [x] Test routes on insomina.


## Screenshots 


 ***PRODUCT ROUTES*** 
***
<img width="1680" alt="Screen Shot 2022-07-16 at 3 52 43 PM" src="https://user-images.githubusercontent.com/101064266/179370913-0a9363a9-3d68-42a7-a7d6-f233b9fc01fe.png">

<img width="1680" alt="Screen Shot 2022-07-16 at 3 52 48 PM" src="https://user-images.githubusercontent.com/101064266/179370912-db60e35f-6ecc-44d7-b7bd-5cc51fcfe606.png">

<img width="1680" alt="Screen Shot 2022-07-16 at 3 52 58 PM" src="https://user-images.githubusercontent.com/101064266/179370910-2c57c126-5379-4cad-a4d3-f121cb663bad.png">

<img width="1680" alt="Screen Shot 2022-07-16 at 3 53 04 PM" src="https://user-images.githubusercontent.com/101064266/179370909-f439d59f-48fb-4541-b6aa-5b356b000a41.png">

<img width="1680" alt="Screen Shot 2022-07-16 at 3 53 13 PM" src="https://user-images.githubusercontent.com/101064266/179370906-d7435bff-4a37-402a-b90f-20abad59fb9d.png">


***CATEGORY ROUTES***
***
<img width="1680" alt="Screen Shot 2022-07-16 at 3 53 29 PM" src="https://user-images.githubusercontent.com/101064266/179370905-1f62968d-d2a9-45a6-a61f-e26b24a06684.png">

<img width="1680" alt="Screen Shot 2022-07-16 at 3 53 39 PM" src="https://user-images.githubusercontent.com/101064266/179370904-c7cff583-3c41-4a78-9684-cf0a0a4cbd84.png">

<img width="1680" alt="Screen Shot 2022-07-16 at 3 53 53 PM" src="https://user-images.githubusercontent.com/101064266/179370902-125f302a-88e7-4ebf-bcb2-48353912630b.png">

<img width="1680" alt="Screen Shot 2022-07-16 at 3 54 49 PM" src="https://user-images.githubusercontent.com/101064266/179370900-4a03dc65-93ec-4ceb-b966-a4a023460090.png">

<img width="1680" alt="Screen Shot 2022-07-16 at 3 55 04 PM" src="https://user-images.githubusercontent.com/101064266/179370899-b8084825-27fe-4965-a481-70c4426df94f.png">



 ***TAG ROUTES***
***
<img width="1680" alt="Screen Shot 2022-07-16 at 3 55 09 PM" src="https://user-images.githubusercontent.com/101064266/179370896-6fddc2cb-73f7-4ac5-ae26-1a0ae2e50b61.png">

<img width="1680" alt="Screen Shot 2022-07-16 at 3 55 18 PM" src="https://user-images.githubusercontent.com/101064266/179370895-3b6f63d0-5177-450c-a185-a8a44ff73379.png">

<img width="1680" alt="Screen Shot 2022-07-16 at 3 55 42 PM" src="https://user-images.githubusercontent.com/101064266/179370893-4ec7525b-2f25-4040-9b59-08ca31e130fe.png">

<img width="1680" alt="Screen Shot 2022-07-16 at 3 56 38 PM" src="https://user-images.githubusercontent.com/101064266/179370892-d31a2df8-6d7f-43bf-a5cc-cda25318a8e9.png">

<img width="1680" alt="Screen Shot 2022-07-16 at 3 58 22 PM" src="https://user-images.githubusercontent.com/101064266/179370891-54e8f226-fd01-4b64-ba43-ca7a95b04012.png">



## Video 
https://youtu.be/7IPwK35TJTc

## Links 
http://localhost:3001/api/categories/
http://localhost:3001/api/tags/ 
http://localhost:3001/api/products/

## Notes
- added "seed": "node seeds/index.js" to scripts in package.json to connect seed files. 
