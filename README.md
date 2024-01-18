# Drop-shop (back-end) e-commerce retail company

## Description

As a manager at an internet retail company,
I want a back end for my e-commerce website that uses the latest technologies,
So that my company can compete with other e-commerce companies

## Table of Contents

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

1. Clone or download this repository as a zip file and open in VSCode


2. Add a .env file to the root of the app with the following information:
```
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='xxxxx'
```

### Application Demo:
* create schema and seed data
    
    ![demo](gifs\sql-demo.gif)
    

* use GET routes to return all categories & all products
    
    ![demo](gifs\GET-demo.gif)
    

* use GET routes to return a single category, product, and tag
    
    ![demo](gifs\GET_by_ID-demo.gif)
    

* use POST, PUT, and DELETE routes for categories
    
    ![demo](gifs\CRUD_cat-demo.gif)
    

* use POST, PUT, and DELETE routes for tags
    
    ![demo](gifs\CRUD_tag-demo.gif)
    

* use POST, PUT, and DELETE routes for products
    
    ![demo](gifs\CRUD_products-demo.gif)
    


## Credits

Starter code used from [Fantastic-Umbrella](https://github.com/coding-boot-camp/fantastic-umbrella) repository on GitHub.com

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Copyright (c) [2024] [Brittney Young]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
