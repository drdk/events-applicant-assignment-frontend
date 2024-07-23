### Assignment Description: Single Page Application for Danish Political Opinion Polls

#### Objective:

Create a simple single-page application (SPA) that reads data from an API endpoint and visually represents the latest opinion poll results for political parties in Denmark. The API endpoint provides information including party ID, percentage votes, and mandates.

#### Requirements:

1. **API Integration**:

   - Fetch data from the provided API endpoint = https://www.dr.dk/nyheder/politik/meningsmaalinger/api/opinionPollData?id=181
   - The API returns a JSON object with the following structure:

     ```json

     ```

   "id": 181,
   "validFromDate": "2022-11-01T00:00:00.000Z",
   "DRPublishDate": "2022-12-20T11:00:00.000Z",
   "headline": "Om det politiske indeks fra den 1. november 2022: ",
   "description": "Indekset er lavet på baggrund af i alt 5.548 gennemførte interviews med repræsentativt udvalgte danskere på 18 år og derover, hvoraf 4.416 (80 pct.) har afgivet et partivalg. Den maksimale usikkerhed på de overordnede resultater er +/÷ 1,7 procentpoint. Interviewene er gennemført den 01. november 2022 - 1. november 2022. OBS: I indekset spørges kun til opstillingsberettigede partier. Blokkenes styrkeforhold er beregnet for de partier, der er over spærregrænsen. Derfor kan opgørelsen ikke direkte sammenlignes med partiernes stemmeandele. ",
   "isElection": true,
   "DRGenerateDate": "2022-12-20T13:20:20.351Z",
   "surveyDataPoints": [
   {
   "id": 9776,
   "partyId": "a",
   "surveyId": 181,
   "segment": "all",
   "percentage": 27.5,
   "mandates": 50
   },
   {
   "id": 9777,
   "partyId": "b",
   "surveyId": 181,
   "segment": "all",
   "percentage": 3.8,
   "mandates": 7
   },
   // ... more data
   ]

   ```

   ```

2. **Front-End Technologies**:

   - Use HTML, CSS, and JavaScript.
   - You may use a front-end framework/library such as React, Vue.js, Angular, or similar if preferred.

3. **Visual Representation**:

   - Create a user-friendly and visually appealing representation of the data.
   - Include a bar chart or pie chart to display the percentage votes for each party.
   - Display the mandates in a tabular format or as part of the chart.

4. **User Interface**:

   - Ensure the application is responsive and works well on different screen sizes.
   - Provide clear labels and legends for the charts.
   - Include a title and brief description of the data being displayed.

5. **Code Quality**:
   - Write clean, well-documented code.
   - Follow best practices for HTML, CSS, and JavaScript.
   - Ensure the application is accessible and performs well.

#### Deliverables:

- A fully functional single-page application.
- Source code hosted on a Git repository (e.g., GitHub, GitLab).
- A README file with instructions on how to run the application locally.

#### Evaluation Criteria:

- Correctness: The application correctly fetches and displays the data.
- Usability: The application is easy to use and navigate.
- Visual Appeal: The data is presented in a clear and visually appealing manner.
- Code Quality: The code is clean, well-documented, and follows best practices.

#### Deadline:

Submit your completed assignment by [insert deadline date].

---

Feel free to reach out if you have any questions or need further clarification. Good luck!
