# Tandem_code_challenge

## Goal
Your goal is to create an application that generates a watering schedule for the next 12 weeks for all of our plants. <br/><br/>
Use creative license in terms of how you want us to see this schedule. At minimum, the plant caretaker looking at the schedule should be able to easily identify which plants to water on a particular date. It could be a user interface (UI), command-line tool, written to file, etc. <br/> <br/>
We would also like to see a README which includes any information about how to run the code, any known issues or complexity we should look out for, and any additional features you would like to have added to make your scheduler even more awesome.

### Before you begin, familiarity with the following concepts will be helpful:
- Arrays and loops
- Date manipulation
- Parsing JSON

## Assumptions
- We do not water our plants on a weekend. Work-life balance is important, and we shouldn't be in the office on a weekend.
- Our plants are reasonably tolerant and will still be happy if they are watered a day before or after the day they should be watered.
- Watering an individual plant takes no time at all so you don't have to worry about how many plants can be watered in a particular day.
- The scheduling should start from next Monday and last for 12 weeks.
- All plants will be watered on the first day of the schedule (next Monday).
- We recognize that when to water a plant is heavily dependent on other factors such as soil, weather, humidity, etc. You can assume that we know exactly when to water these specific plants.
- You have been provided a JSON file which contains data for our plants.
## Acceptance Criteria
- The user can view which plant(s) to water on which date(s).
- The schedule covers the next 12 weeks starting next Monday.
- No plants are watered on Saturdays or Sundays.
- Each plant is watered on its desired schedule or as close as possible, taking into account weekends.

## How to run the program

click on the link:
https://colab.research.google.com/github/prevelat/Tandem_code_challenge/blob/master/TandemCodeChallenge.ipynb

save a copy of the notebook in your drive: <br/>
<img src="https://github.com/prevelat/Tandem_code_challenge/blob/master/copy_notebook.png" width="300">

run environment and follow instructions: <br/>
<img src="https://github.com/prevelat/Tandem_code_challenge/blob/master/run.png" width="300">
