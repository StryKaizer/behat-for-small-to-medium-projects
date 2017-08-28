
          <h3>behat.yml</h3>
          <pre>
            <div class="behatyml">
              default:
                suites:
                  default:
                    contexts:
                      - FeatureContext
                      - Drupal\DrupalExtension\Context\DrupalContext
                      - Drupal\DrupalExtension\Context\DrushContext
                      - Drupal\DrupalExtension\Context\MessageContext
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
            </div>
          </pre>
          <h4>Ref. <a href="http://drupal.org/project/drupalextension">http://drupal.org/project/drupalextension</a>
</h4>
        