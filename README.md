# pith-pack-md-icons
Pack Material Icons for Pith

-------

# About

This project packs Material Icons and Material Symbols so that they can be used with the Pith Framewok.

For info on Material Icons / Material Symbols, visit the Material.io website at https://m3.material.io/styles/icons/overview, see the guide at https://developers.google.com/fonts/docs/material_icons, see the repository at https://github.com/google/material-design-icons/ and the font website at https://fonts.google.com/icons

For info on Pith, see the Pith website at https://pith-framework.org/

# Install

Install to an existing Pith Framework project

Use Composer to install pack to the `vendor` folder.
```bash
php composer.phar require pith-front/pith-pack-md-icons
```

Add new route to your Route List:

```php
public array $routes = [
    // Other routes....
    // ...
    
    // Add route to call md-icons from
    ['route', 'GET', '/resources/vendor/library/md-icons/{filepath:.+}', '\\PithFront\\PithPackMdIcons\\MdIconsResourceRoute'],
];
```

-------------


# Licensing Info

### Material Icons *and* Material Symbols
- Material Icons
- Material Symbols
- Copyright: Copyright 2018 Google, Inc. All Rights Reserved.
- Released under license:  Apache License, Version 2.0
- *"We have made these icons available for you to incorporate into your products under the Apache License Version 2.0. Feel free to remix and re-share these icons and documentation in your products. We'd love attribution in your app's about screen, but it's not required."* -- Material Icons / Material Symbols README file.
- Material Design is a design language developed by Google in 2014.
- Google does not currently maintain the npm package, past v3 (2016), However, @marella hosts the updated versions.

### pith-pack-md-icons
- pith-pack-md-icons
- Copyright (c) Ian Maurmann
- Released under license: Apache License, Version 2.0
- Link: https://github.com/pith-front/pith-pack-md-icons