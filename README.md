# Angular_pokoman_E2E_testing_demo
# Details:- 
In our Pokédex app, the user can open a modal to see details about specific Pokémon and then use the arrow keys to navigate between Pokémon. We would like to write an E2E test to make sure this functionality works in our application. E2E test automatically opening a browser and running through our tests to make sure our application is behaving correctly.
# Protractor:- 
Protractor is an E2E test runner that can take scenario tests and run them in the browser for us. The test code itself is written using Jasmine. # Jasmine # is a testing library the provides all the assertion and utility functions needed to write unit and E2E tests.
Our E2E test is using Jasmine. We first describe our E2E test. Then we import our Page Object class to use and create a new NgPokedexPage instance in the beforeEach function. This will create a new isolated test page for each E2E test. With Jasmine we give a description of the test with the it() function. The it function takes a function to execute and runs an expectation to make sure the test passes.
Protractor makes E2E and integration tests easy for Angular apps. Protractor knows when to run and check the DOM after Angular has done rendering the page. Although Protractor was designed primarily for Angular, there are a few gotchas for Angular.
