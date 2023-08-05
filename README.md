# SimplyDotEnv

A simple DotEnv component for working with environment variabls in .env file (decoupled from CI4)

## Usage

```php

$dotenv = new SimplyDi\Dotenv(__DIR__); // directory where .env is present
$dotenv->load(); // load the vars from .env file

echo $_ENV['DEBUG']; // or getenv('DEBUG')

```