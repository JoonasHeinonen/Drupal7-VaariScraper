# Vaari Scraper

## Description

Vaari Scraper is a module developed in Drupal 7 as a scraping tool. This tool scrapes wanted DOM elements with given attributes (e.g. class or id) from the given URL. It stores and displays the scraped data directly to the user after scraping. It also posts data from the scraped websites to the Drupal 7 database.

## Architectural Schema

Core version of Drupal and used APIs in Vaari Scraper:

|Version|Used APIs in development|
|----|-----|
|Drupal 7|Form API, Schema API, Database API|

Folder structure of the module:

- vaariscraper.info
- vaariscraper.module
- vaariscraper.install
- /css
    * main.css
- readme.md

## Downloading

### Step 1.

In command line, navigate yourself to the local installation of your Drupal 7 website. Here, navigate yourself with the following command to your modules folder:

```CMD
cd sites/all/modules
```

### Step 2.

To clone the repository for the module with Git, type the given command for cloning:
```git
git clone https://github.com/JoonasHeinonen/Drupal7-VaariScraper
```
You have now cloned Vaari Scraper into your modules folder.

## Installation

This documentation does not go through the installation process of Drupal 7 and is for the module installation.

### Step 1.

Now run the HTTP-server (e.g. if you're using XAMPP, local installation is located in **_c:/xampp/htdocs/drupal7/_**) to start your Drupal 7 installation. After logging in, here, navigate to your modules tab. Scroll down to find the module and activate it.

### Step 2.

This will initialize new table in the database your Drupal 7 is using. This table stores all the data of scraped websites, the results and you can see them in display tag.

### Congratulations! You have now installed Vaari Scraper!