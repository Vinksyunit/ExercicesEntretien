# Exemple de classes PHP 

```php
<?php

namespace MonApp\Models;

use MyLib\ORM\Model;

class User extends Model {
    private $table = 'users';

    // ...
}
```