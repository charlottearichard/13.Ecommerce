# 13.Ecommerce


## Game Plan 

1. Set up project: Set up repo, identify issues. 
2. Scaffold application's architecture: Install npm packages. 
3. Create models (category, product, tag, productTag). 
4. Create routes 
5. Test routes with insomnia.

## Tasks 
<p> ✅ Install npm packages (mysql2, sequelize, dotenv) </p>

<p> ✅ Connect schema to database: </p>

* put sql password and username in .env file (this is conected to 'connection.js')
* .gitignore env file 
* mysql -u root -p (log-in w/ password)
* source db/schema.sql
* show databases; (to check if datbase has be successfully created)
* use ecommerce_db; (to change into this database)

<p> ✅ Define 'Category' columns (id: interger dataType, false allowNull, true primaryKey, true autoIncrement. category_name: string dataType, false allowNull. </p>
