### behat.yml

```
default:
  suites:
    default:
      contexts:
        - FeatureContext
        - Drupal\DrupalExtension\Context\DrupalContext
        - Drupal\DrupalExtension\Context\MinkContext
  extensions:
    Behat\MinkExtension:
      goutte: ~
      selenium2: ~
      base_url: http://mysite.local/
    Drupal\DrupalExtension:
      blackbox: ~
      api_driver: 'drupal'
      drupal:
        drupal_root: '/var/www/mysite'
```

Ref. [http://drupal.org/project/drupalextension](http://drupal.org/project/drupalextension)
