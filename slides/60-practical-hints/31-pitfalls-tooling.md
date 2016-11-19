## Tooling Pittfalls 

* Browser & Protractor & Webdriver must be compatible
   * At least one of them is installed globally
   * Rolf's recommendations:
     * Install Protractor and Webdriver also globally
     * Let developer control when to update
     * Causes less dependency problems for developers
   * Other Option: use a versioned docker image to run tests
