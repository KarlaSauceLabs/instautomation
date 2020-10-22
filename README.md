# Instautomation

## Requirements 

* Ruby `2.7.2`
* Rails `6.0.3.4`
* Node.js  `12.x`
* Yarn `1.22.x`
* SQLite3 `3.28.0`

## Setup

### Local Setup
1. Clone repository: `https://github.com/ely-saucelabs/instautomation.git`
1. cd `instautomation`
1. Check you have all your dependencies installed:
   * `ruby -v`
   * `rails -v`
   * `node -v`
   * `yarn -v`
   * `sqlite3 --version`
1. Run the setup script: `bin/setup`
1. Run Tests: `rails test -v`
1. Run System Tests: `rails test:system -v`
1. Start the server: `rails server`
1. Open: http://127.0.0.1:3000
1. The app is running :tada:

## How to run tests?

`rails test` or `rails test -v`

Or run an individual test with `rails test path/to/individual_test_rb` or `rails test -v path/to/individual_test_rb`

> -v, --verbose Verbose. Show progress processing files.

### System Tests

By default, running `rails test` won't run system tests, so we need to use: 

`rails test:system`

## Deployment

* **Production**: Deployments are triggered manually in [Heroku](https://www.heroku.com/).
* **PR**: With every PR that is opened, a [Review App](https://devcenter.heroku.com/articles/github-integration-review-apps) is created in  [Heroku](https://www.heroku.com/) with a deployment of the code from the PR. 

## With credits to :heart:

* [Font Awesome](http://fontawesome.io/)
* [Bootstrap](http://getbootstrap.com/)
* [Subtle Patterns](www.toptal.com/designers/subtlepatterns/)

## References :bulb:

* [Ruby on Rails Guides](https://guides.rubyonrails.org/) 
* [Ruby on Rails Guides > Testing](https://guides.rubyonrails.org/testing.html)
* [Rails Girls App Tutorial](http://guides.railsgirls.com/app)
