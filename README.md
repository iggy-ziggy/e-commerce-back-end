# E-Commerce Back End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Table of Contents

* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Tests](#tests)
* [Questions](#questions)

## Description

A functional back end for an e-commerce site. It will allow a user to seed a database with test data so that routes and requests can be tested.

## Installation

git clone git@github.com:iggy-ziggy/e-commerce-back-end.git

## Usage

In the terminal, log into mysql and type the following:

source db/schema.sql;

use ecommerce_db;

quit

Once out of mysql, type the following:

node seeds/index.js

npm start

The database has now been created and seeded with data to test. 
Using Insomnia, you can perform requests to make sure the database and routes are working correctly.
Using `http://localhost:3001`, the following endpoints can be used:

/api/categories/  
/api/tags/  
/api/products/

GET, POST, PUT, and DELETE requests can be made to each of these.

<img width="996" alt="Screenshot 2023-08-21 at 11 46 20 AM" src="https://github.com/iggy-ziggy/e-commerce-back-end/assets/128410000/81614468-bd9c-4d82-859d-4285c0f68bd4">
<img width="685" alt="Screenshot 2023-08-21 at 11 47 30 AM" src="https://github.com/iggy-ziggy/e-commerce-back-end/assets/128410000/2586ffc2-cbc5-4f92-86ff-4157fbf0c95e">
<img width="660" alt="Screenshot 2023-08-21 at 11 47 47 AM" src="https://github.com/iggy-ziggy/e-commerce-back-end/assets/128410000/8dab4ccf-56e6-4f03-856e-fef8396844ca">
<img width="670" alt="Screenshot 2023-08-21 at 11 48 26 AM" src="https://github.com/iggy-ziggy/e-commerce-back-end/assets/128410000/38ea8ed9-e676-4561-aa5e-1443cc22ec9e">

## License
[Link to MIT License](https://opensource.org/licenses/MIT)

## Contributing

n/a

## Tests

n/a

## Questions

GitHub Profile: (https://github.com/iggy-ziggy)

If you have any questions, feel free to contact me at:
merkabafox@gmail.com

