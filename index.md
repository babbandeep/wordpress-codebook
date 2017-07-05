# index.php

```php

define('WP_USE_THEMES', true);

require( dirname(__FILE__) . '/wp-blog-header.php');

```
**php code**

```php
define();
require();
dirname();
__FILE__

```
**Wordpress code**

WP_USE_THEME

[used in files](https://github.com/WordPress/WordPress/search?utf8=%E2%9C%93&q=WP_USE_THEMES&type=)


# wp-blog-header.php

```php

if( !isset($wp_did_header)){
    $wp_did_header = true;
    
    require_once( dirname(__FILE__) . /wp-load.php);
    
    wp();
    
    require_once( ABSPATH . WPINC . '/template-loader.php' );
}

```

**php code**

```php
isset()
require_once();
```

**Wordpress code**

$wp_did_header
wp()
ABSPATH
WPINC
