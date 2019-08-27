# Packagist Test

This project was created just to test code publishing on Packagist

### Installing

Use composer:

```
composer require apankov/hello
```

### Example

add autoloader:

```
require_once "vendor/autoload.php";
```
namespace:
```
use APankov\Hello\HelloWorld;
```
run and enjoy:
```
echo HelloWorld::hello();
```
