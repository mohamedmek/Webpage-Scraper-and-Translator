
# Website Scraper and Translator

This PHP script scrapes a website and translates its HTML content to a target language using Microsoft Translator API. The script also extracts CSS files, JS files, and images from the website and saves them to their respective directories.

## Requirements

- PHP 7.4 or higher
- Composer
- Google Chrome browser

## Installation

1. Clone this repository to your local machine.
2. Run `composer install` to install the necessary dependencies.
3. Set your Microsoft Translator API key in the `$apiKey` variable in `index.php`.
4. Set the base URL of the website you want to scrape in the `$baseUrl` variable in `index.php`.
5. Set the target language you want to translate the HTML content to in the `$targetLanguage` variable in `index.php`.
6. Run `php index.php` to start scraping and translating the website.
