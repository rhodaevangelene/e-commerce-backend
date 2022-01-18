# E-Commerce Backend
This project was built for module 13 to demonstrate Object-Relational Mapping, or ORM. This project utilizes Express, Sequelize, and MySQL to store, update, remove, and add items in a shopping catalouge for an E-Commerce web page.

## Installation and operating guide

### Installation Guide
Clone the repository and run the following command to install all dependencies.
```cd Develop```
```npm install```

### Operating Guide
After successfully installing your npm's you will need to log in to MySQL to start the app.

```mysql -u root -p```

Enter your password when promted

```source db/schema.sql```

```quit```

```npm run seed```

```npm start```

You should now be able to use Insomnia to try out the database by using Get, Put, Post, and Delete requests

## Walkthrough Video
TODO: Walkthrough Video

## Contributors
Rhoda Evangelene

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[ISC](https://choosealicense.com/licenses/isc/)