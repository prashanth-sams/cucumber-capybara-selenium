Cucumber-Capybara-Selenium_WebDriver Integration
=========

Selenium WebDriver is the most popular web auotmation tool


To Run tests in Terminal

    $ bundle exec cucumber features/googlesearch.feature



How to Use
------------

Install selenium-webdriver

    $ sudo gem install selenium-webdriver


Add selenium-webdriver in your Gemfile

    $ gem "selenium-webdriver"


Set the Selenium WebDriver to selenium in env.rb

    Capybara.default_driver = :selenium
