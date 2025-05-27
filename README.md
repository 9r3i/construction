# construction
under-construction web page


# header
if working with php, example:
```php
<?php
defined('MSERVER_FILE') 
  or define('MSERVER_FILE','server/mserver.php');
if(is_file(MSERVER_FILE)){
  @require_once(MSERVER_FILE);
  exit;
}
```
this sample for mserver library only.
when the file's ready, then the construction won't be loaded.


# usage
1. rename `index.php.txt` to `index.php` if workig with php
2. rename `index.txt` to `index.html` if just for covering up the web

