# Web Scraping: Wikipedia Article Scraper

This Python project scrapes data from Wikipedia based on a user-specified topic to create text file.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Functionalities](#functionalities)
- [Usage](#usage)
- [Example](#example)

## Introduction
Web scraping is a technique used to extract data from websites. In this project, we focus on scraping data from Wikipedia articles. Users provide a topic name, and the program fetches relevant content from the corresponding Wikipedia page.

## Technologies Used
- Python: Main programming language for the project.
- Requests: Used for making HTTP requests to fetch web pages.
- BeautifulSoup: A Python library for parsing HTML and XML documents.

## Functionalities
* **User Input:** Prompts the user to enter a topic name.
* **Web Scraping:**
    * Utilizes `requests` library to fetch the Wikipedia article URL based on the user-provided topic.
    * Employs BeautifulSoup (`bs4`) to parse the HTML content of the retrieved webpage.
* **Data Extraction:**
    * Iterates through paragraphs (`<p>`) tags to accumulate factual content.
    * Removes unnecessary elements like bracketed references ([1], [2], etc.).
* **File Creation:**
    * Saves the extracted data (article title and factual content) into a text file named after the Wikipedia article title with a `.txt` extension.
    * Uses UTF-8 encoding for broader character compatibility.
 
## Usage
1. Run the Python script.
2. Input the desired topic name when prompted.
3. The program fetches data from the Wikipedia page related to the topic and saves it in a text file.

## Example
Suppose the user enters "Artificial Intelligence" as the topic. The program will fetch data from the Wikipedia page on Artificial Intelligence and save it in a text file.
