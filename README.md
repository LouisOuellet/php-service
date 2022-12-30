![GitHub repo logo](/dist/img/logo.png)

# phpService
![License](https://img.shields.io/github/license/LouisOuellet/php-service?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/LouisOuellet/php-service?style=for-the-badge&logo=github)
![GitHub top language](https://img.shields.io/github/languages/top/LouisOuellet/php-service?style=for-the-badge)
![Version](https://img.shields.io/github/v/release/LouisOuellet/php-service?label=Version&style=for-the-badge)

## Features
 - Service

## Why you might need it
If you are looking for an easy start for your PHP Service. Then this PHP Class is for you.

## Can I use this?
Sure!

## License
This software is distributed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html) license. Please read [LICENSE](LICENSE) for information on the software availability and distribution.

## Requirements
* PHP >= 8.0

## Security
Please disclose any vulnerabilities found responsibly – report security issues to the maintainers privately.

## Installation
Using Composer:
```sh
composer require laswitchtech/php-service
```

## How do I use it?
### Example
```php
#!/usr/bin/env php
session_start();

//Import phpCLI class into the global namespace
//These must be at the top of your script, not inside a function
use LaswitchTech\phpCLI\phpCLI;

//Load Composer's autoloader
require 'vendor/autoload.php';

// Interpret Standard Input
if(defined('STDIN') && !empty($argv)){

  // Start Command
  new phpCLI($argv);
}

```
