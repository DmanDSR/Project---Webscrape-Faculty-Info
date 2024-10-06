# Project - Webscrape-Faculty-Info
 Little web scraping  project to update the professor list

## Project Overview 

I was assigned to update an Excel file with information on the current faculty in the ECE Department, but I decided to turn it into a small project. Using Python, Beautiful Soup, pandas, and a custom module I created for data-related tasks, I scraped the relevant information from the department's website. In the end, I merged two separate lists to create a consolidated, up-to-date faculty list.

[Faculty Site](https://ece.fiu.edu/people/faculty/#)

<img width="407" alt="image" src="https://github.com/user-attachments/assets/01a38075-9a42-4968-bc21-acad372c38d9">

## Issues had

During this project, I encountered challenges accessing and parsing data wrapped in p tags, particularly when ensuring the correct identification of professors by their last names while preserving the original Excel document's styling. The complexity increased due to variations in the professor names—some included middle names or were as short as two letters—which made filtering and handling names more difficult. To maintain efficiency, I limited myself to a few hours of work over two days, which added an extra layer of urgency to the task.

## Future Improvements

I plan to enhance the project by implementing a method to remove middle names, leaving only the first and last names of the professors. Additionally, I aim to maintain the original formatting of the Excel document during data processing. Expanding the functionality to access and extract other relevant information from the remaining p tags is also a key area for improvement.
