In this challenge, you'll create a Flutter app that utilizes the Star Wars API (SWAPI) to display data about Star Wars characters in a table.

## Instructions

1. **Set Up Project:**
   - Set up a new Flutter project using your preferred IDE or Flutter CLI.
   - Ensure you have the necessary dependencies installed for making HTTP requests and building UI components.

2. **Fetch Data from SWAPI:**
   - Use the http package to make GET requests to the SWAPI (https://swapi.dev/api/people/).
   - Retrieve data about Star Wars characters from the API. Each character object should include attributes such as name, height, mass, hair color, etc.

3. **Display Data in a Table:**
   - Design a table UI component to display the fetched data in a tabular format.
   - Each row in the table should represent a character, and each column should display a specific attribute of the character.

4. **Handle Loading and Error States:**
   - Implement loading and error states to provide feedback to the user while the data is being fetched or in case of any errors during the API request.