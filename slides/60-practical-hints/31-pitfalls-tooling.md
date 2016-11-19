## Tooling Pittfalls 

* Browser & Protractor & Webdriver must be compatible
   * At least one of them is installed globally
   * Rolf's recommendations:
     * Install Protractor and Webdriver also globally
     * let every developer control when to update
     * causes less dependency problems for devs
   * Other Option: use a versioned docker image to run tests
