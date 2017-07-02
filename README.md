# SecureParsedown

Parsedown, with added XSS protections.

Enable these with

```php
<?php

use Aidantwoods\SecureParsedown\SecureParsedown;

$Parsedown = new SecureParsedown;
$Parsedown->setSafeMode(true);
```

More info about this can be found at https://github.com/erusev/parsedown/pull/495

---

SecureParsedown is an extension to Parsedown. Parsedown was created by
Emanuil Rusev, and is available from https://github.com/erusev/parsedown.