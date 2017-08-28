
          <h2>Tags</h2>
          <pre>
            <code class="gherkin">
              # This test will use the Drupal API.
              @api
              Scenario:
                Given I am logged in as an administrator
                ...

              # This test will run in an actual browser.
              @javascript
              Scenario:
                Given I am on the homepage
                ...
            </code>
          </pre>
        