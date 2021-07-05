### Hi there 👋

<!--
**khoivan88/khoivan88** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

I am an organic chemist who writes apps and creates websites!!

## A few of the websites that I created:

- [https://kristufeklab.com/](https://kristufeklab.com/): an academic chemistry research group website. *Tech stack*: static site generator (11ty), snowpack, Tailwindcss, AlpineJS.
- [https://organicchemistrydata.org/](https://organicchemistrydata.org/): a supplemental website launched by the Division of Organic Chemistry (DOC) in Sept 2020 for a collection of organic chemistry data. *Tech stack*: static site generator (11ty), snowpack, bootstrap4, vanilla javascript, jQuery.
- [https://organicchemistrydata.org/hansreich/](https://organicchemistrydata.org/hansreich/): an archive of the late Professor Hans Reich’s (University of Wisconsin - Madison) web collection, transferred and currently being maintained by the DOC. While I did not create the content (~ 700 HTML pages) of this collection, the original materials were converted to a mobile-friendly format to work well for users from desktops, laptop, tablets and cell phones. *Tech stack*: static site generator (11ty), snowpack, bootstrap4, vanilla javascript, jQuery.
- [https://eluenttranslator.netlify.app](https://eluenttranslator.netlify.app): a web utility to estimate a solvent mixture composition that would give similar eluent strength for chromatography. *Tech stack*: static site generator (11ty), snowpack, Tailwindcss, AlpineJS.
- [https://acs-s21-orgn.netlify.app/dates/](https://acs-s21-orgn.netlify.app/dates/): a website to display a schedule of presentations in the ORGN track that were listed by date (for better viewing compared to the original ACS Spring 2021 scheduler). The content of the website was automatically extracted and updated 4 times/ day from the ACS Spring 2021 website. *Tech stack*: python, scrapy, github action, static site generator (11ty), snowpack, Tailwindcss, AlpineJS.
- [https://cs50w-pro1.herokuapp.com/](https://cs50w-pro1.herokuapp.com/): a website contains a database of 5000 books with links to GoodReads and OpenLibrary.org databases. Users will be able to register for website and then log in using their username and password. Once they log in, they will be able to search for books, leave reviews for individual books, and see the reviews made by other people. A third-party API by Goodreads, another book review website, is also used to pull in ratings from a broader audience. *Tech stack*: python, flask, SQL, HTML, CSS, vanilla javascript.
- [https://doyouknowwhenyouwillgraduate.netlify.app/](https://doyouknowwhenyouwillgraduate.netlify.app/): a fun little website for any graduate student dealing with people keep asking them when they will graduate. *Tech stack*: static site generator (11ty), snowpack, Tailwindcss, AlpineJS.
- [https://open-enventory.gitbook.io/user-guides/](https://open-enventory.gitbook.io/user-guides/): create the User Guides content of Open Enventory 

## A few of softwares/apps that I created:

- [https://github.com/khoivan88/find_sds](https://github.com/khoivan88/find_sds): Find safety data sheet (SDS) for chemicals using their CAS numbers. *Tech stack*: python, requests, BeautifulSoup.
- [https://github.com/khoivan88/pka_lookup](https://github.com/khoivan88/pka_lookup): Python script to lookup pKa values, current database of at least 7300 values. *Tech stack*: python, PubChemPy, requests, pandas, tinyDB
- [https://github.com/khoivan88/open_enventory-modified_for_US](https://github.com/khoivan88/open_enventory-modified_for_US): modified version of Open Enventory, free open-source Chemical Inventory and ELN. *Tech stack*: LAMP stack, PHP, SQL, HTML, javascript. 
- https://github.com/khoivan88/chemjobber-faculty-jobs-list-automation: Extract chemistry faculty job postings every hour from for different job posting boards, save to csv file and display to google sheet. The script is automatically run with github action every hour to extract job listing and the details of each of the listing. *Tech stack*: python, scrapy, google sheet API.

## Automation workflows:

1. Chemical inventory workflow automation:
    
    Tasks include:
    - Logging in and extracting (download, csv format) inventory data for the current date in one software
    - Sanitizing data and Processing data for importing to another software: removing unwanted data, changing the date format, changing CSV format to tab-separated text, extracting some critical info (chemical structures) into their own files.
    - Logging into another inventory software and importing the newly processed data
    - Keeping logs for the whole process
    - Cleaning up log files, data files using dynamic info of available disk size, how old the data, log files are.
    - Error reporting using email if there is any issue during the whole process

    Challenging:
    - Web automation requires headless selenium on a remote virtual private server (VPS): much more challenging to set up on a rented virtual private server.
    - Web automation set up on a VPS with limited CPU and RAM
    - Cronjob setting up for non-root user (because of selenium) while also performing tasks requiring admin permission.

    Tech stack:
    - Python
    - Selenium (headless, running on xvfb for remote headless virtual private server)
    - Requests
    - Pandas

    ![Solution Program Overview with UML Diagram](https://user-images.githubusercontent.com/33493502/124502455-89649980-dd91-11eb-94ac-ea26d34b3c26.png)

## My skills and experience include

- Python, PHP
- Static site generator with [11ty](https://www.11ty.dev/)
- HTML and (S)CSS
- Responsive Web Design
- Accessibility and Progressive Enhancement
- Vanilla JavaScript
- Git, and Continuous Integration
- Docker

## How to reach me

📧: knv88@pm.me

## How to support me?

If you enjoy using my softwares/apps/websites and can afford it, you can [buy me a coffee](https://www.buymeacoffee.com/KhoiVan) 🙏 !
