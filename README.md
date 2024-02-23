# String Utils

---

Simple string utils for dealing easier with them

# Installation

Install using composer:

‌```
composer require khorashadi/string-utils
‌```

# Example

‌```php
<?php

require __DIR__.'/vendor/autoload.php';

use \khorashadi\StringUtils\Str;

var_dump(Str::contains('abcd', ['ab', 'x']));
‌```
