# Implementation

### **Inputs**
The inputs for using the plugin are:  

| **Field** | **Example** | **Description** |
| :--- | :--- | :--- |
| wordpress_plugin_name | wp-stackspot-plugin | Wordpress :: Plugin Name |
| wordpress_plugin_uri | https://www.your-site.com/ | Wordpress :: Plugin URI |
| wordpress_plugin_description | Plugin description | Wordpress :: Plugin Description |
| wordpress_plugin_version | 0.1 | Wordpress :: Plugin Version |
| wordpress_plugin_author | Author Name | Wordpress :: Plugin Author |
| wordpress_plugin_author_uri | https://www.your-site.com/ | Wordpress :: Plugin Author URI |

### Scaffold

The plugin will create the initial folder structure for a plugin, inside the WordPress plugins base folder together with the creation of the ``wp-<PLUGIN_NAME>.php`` file.

The purpose of this plugin is just to create a base structure for its development, all the plugin logic will have to be implemented later. 

```php
<?php
/**
* Plugin Name: wp-stackspot-plugin
* Plugin URI: https://www.your-site.com/
* Description: Plugin description
* Version: 0.1
* Author: Author Name
* Author URI: https://www.your-site.com/
**/
```

### Additional Settings

N/A
