##### Full Stack developer - Coding challenge

The following Coding challenge project must be completed and sent over prior to an onsite/remote technical interview at FIIX.

###### General Instructions

1. There is a 1-week deadline to submit a solution, however we ask you not to spend more than a couple of hours to provide a clean and working solution.
2. You may leave things open for discussion during the onsite/remote technical interview.
3. Feel free to get in touch with ..... if you have any questions.

###### Project Description

The goal of the challenge is to build a Plant Care system that focuses on a watering schedule.
Given a data set containing the names of plants at a nursery, their watering frequency and when they were watered last,
present a time table displaying plants that have been watered, that will need watering soon and those that have watering overdue.

###### SPA
1. Build a basic SPA, either within the provided maven base project or in a different project with a basic tabular component.
2. The time table must display plant names, watering frequency, last watered date and status.
3. Status cells should be text-free but will show one of four colours Green, light green, yellow and red.
4. Status - Green denotes that the plant has been watered as per their frequency requirement.
5. Status - Light green denotes that the plant is due to be watered today or in 1 day.
6. Status - Yellow denotes that watering the plant is overdue by 1 or 2 days.
7. Status - Red denotes that watering the plant is overdue for more than 2 days.

###### Spring Boot backend
1. Provide an API to consume the current watering data set. This maybe invoked via a tool like Postman or curl.
2. Use the H2 database to persist the data set. Feel free to change to a more familiar DB if required.
3. Provide an API that the SPA will consume in order to populate the Watering Time Table.

###### Project Instructions
1. Ensure to follow clean code and SOLID principles.
2. Follow TDD or ensure to have good test coverage.
3. Ensure to follow good coding style and conventions

###### Submission Instructions
1. Clone the repository
2. Complete your project as instructed and ensure to commit all the code to your local repo.
3. Create a git bundle and email it to ....



