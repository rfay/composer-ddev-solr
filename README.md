# composer-ddev-solr

A composer recipe to implement a solr service as described in [ddev docs](https://ddev.readthedocs.io/en/stable/users/extend/additional-services/#apache-solr)

Install with `ddev composer require rfay/composer-ddev-solr` or `composer require rfay/composer-ddev-solr`

You temporarily need to add two additional repositories into composer.json to use this, for example:

```json
    "repositories": [
        {
            "type": "composer",
            "url": "https://packages.drupal.org/8"
        },
        {
            "type": "vcs",
            "url": "https://github.com/rfay/composer-ddev-solr"
        },
        {
            "type": "vcs",
            "url": "https://git.4viewture.eu/ddev/composer-ddev"
        }
    ],
```
