## iOS Developer Challenge

Thank you for applying to hear.com as an iOS developer. We would like to get a general idea of your expertise and give you the chance to show us your skills.

This challenge will involve converting an open source weather app to display population of the cities instead. We use the Zip code in our business to direct new leads to correct business models, so this zip data is very relevant for our business

**The challenge**

 * Create a github repo with https://www.raywenderlich.com/4161005-mvvm-with-combine-tutorial-for-ios code so we can easily see your changes.
 * Make the app ask for zip code instead of the City.
 * Create a backend in any language you like that has a MySQL server with one table called zipcodes from https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-zip-code-data-soi
 * Have an API endpoint that when you input Zip code it outputs the json with the correct row. Include a Postman screenshot of how you call the API.
 * Change the weather app to display the Population, and percentage of Eldery tax returns, instead of weather, when zip code is entered.

**Things to focus on**

 * Minimum changes to the SwiftUI from the example app, we need to evaluate your code and your understanding of existing code and infrastructure.
 * MVVM architecture, make sure you debounce the Zip code entry.
 * Speed optimization.
 * Attention to design details.

**Tech Requirements**

- Have some build script for the backend, it should run on a Mac and have a migration that sets up the database and opens a port to listen.
- The Combine app should have two schemas, one for localhost and other named "prod" which will use a fictious server named production.com.

**Setting**

We expect you to invest about 4-8 hours for this challenge. We prefer quality over quantity. The level of feature completeness, documentation, tests is subject to your decision making. Feel free to make any trade-offs and document your decisions. Think: product management is on vacation and not available.

**Deliverable**

Please provide us a link to a git repo with your source code and instructions on how to run the code. Make sure it works out of the box and briefly describe your solution and explicitly mention any trade-offs and simplifications. Put instructions and a description in a README file.
