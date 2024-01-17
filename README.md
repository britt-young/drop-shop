# Drop-shop (back-end) e-commerce retail company

## Description

As a manager at an internet retail company,
I want a back end for my e-commerce website that uses the latest technologies,
So that my company can compete with other e-commerce companies

## Table of Contents

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

Install necessary npm packages and save as dependencies in your package.json file
```
npm install mysql2 sequelize dotenv --save
```

## Usage

1. Add a .env file to the root of the app with the following information
```
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='xxxxx'
```

2. Do this.....

### Application Demo:
* create schema and seed data
    
    ![demo](utils\sql-demo.gif)
    

* use GET routes to return all categories & all products
    ```md
    ![demo](assets/images/screenshot.png)
    ```

* use GET routes to return a single category, product, and tag
    ```md
    ![demo](assets/images/screenshot.png)
    ```

* use POST, PUT, and DELETE routes for categories
    ```md
    ![demo](assets/images/screenshot.png)
    ```

* use POST, PUT, and DELETE routes for tags
    ```md
    ![demo](assets/images/screenshot.png)
    ```

* use POST, PUT, and DELETE routes for products
    ```md
    ![demo](assets/images/screenshot.png)
    ```


## Credits

Starter code used from [Fantastic-Umbrella](https://github.com/coding-boot-camp/fantastic-umbrella) repository on GitHub.com

## License

The last section of a high-quality README file is the license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, refer to [https://choosealicense.com/](https://choosealicense.com/).