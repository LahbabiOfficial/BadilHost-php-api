# Description
This client is used to interact with one of the following APIs:
 * BadilHost ([Docs](resellerclub-php-api/kb/answer/751))
 
Available API requests: 
* Actions
* Contacts
* Customers
* Domains
* Products

## Installation
```console
composer require LahbabiOfficial/BadilHost-php-api
```

## Usage Example
```php
use LahbabiOfficial\BadilHost\ResellerClub;

$resellerClub = new ResellerClub('<userId>', '<apiKey>');
$resellerClub->domains()->available(['google', 'example'], ['com', 'net']);
```
Note: All functions return a raw response from API.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

 
