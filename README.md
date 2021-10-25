# HTML form , input , for searching google
*You can only use HTML tags with NO CSS to achieve the user interface.<br/>
*Enable submiting the form only if there is text in the search text and 1 to 25 search results.(only using html input attributes)<br/>
1. Create an index.html file with html structure
2. Add form to html body that will collect the user's data 
3. In the form collect the :<br/>
a. Text input that will contain the search query text (q)<br/>
b. Select with options of when the pages were first indexed (as_qdr)<br/>
c. Numeric input that will hold the number of results shown (num)<br/>
d. Checkbox that when checked it will limit the results to hebrew (lr)<br/>
*for explantion about the parameters to send google use https://moz.com/blog/the-ultimate-guide-to-the-google-search-parameters
4. Submit button with "Ask google" text
5. When clicking Submit button , send the user input to "https://google.co.il/search" and open the results in a black page. 