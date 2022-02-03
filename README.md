## Install

- Since our repository is private, append this in your `composer.json` file

```
    "require": {
        ...
        "integratrcorp/baserepository": "^0.1"
    },
    {
        "repositories": [{
            "type": "vcs",
            "url": "https://github.com/IntegratrCorp/baserepository"
        }]
    }
```

- Publish package config `php artisan vendor:publish --tag=baserepository --force`

- Run `composer install`