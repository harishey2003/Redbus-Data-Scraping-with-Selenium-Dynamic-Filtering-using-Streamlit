Project-1
Redbus Data Scraping with Selenium &amp; Dynamic Filtering using Streamlit

1.1 INTRODUCTION:
•	The Data scraping from dynamic websites like Redbus can provide real-time insights into bus services, schedules, prices, and availability. For this project, Selenium is employed to extract data from Redbus, which uses dynamic content rendering via PYTHON, and Streamlit serves as the interface to interactively filter and display the data.

1.2 DOMAIN:
•	Transportation

1.3 SKILLS USED IN PROJECT:
1.Python
2.Selenium
3.Pandas
4.MySQL
5.Streamlit.

1.4 FEATURES:
1. Data Scraping with Selenium
Selenium is a powerful tool for automating web browsers and scraping data from dynamic sites that rely on python. In the case of Redbus, data is often loaded dynamically based on user inputs such as the origin, destination, and date. Here, Selenium mimics user actions to capture the relevant information.
2. Dynamic Filtering with Streamlit
Once the data is scraped, it can be presented to users for further analysis and filtering. Streamlit is a great tool for building interactive dashboards that allow users to filter and visualize the scraped data dynamically.


1.5 PACKAGES AND LIBRARIES:
1.pandas as pd
2.pymysql.connect
3.import datetime
4.streamlit as slt
5.from streamlit_option_menu import option_menu
6.from selenium import webdriver
