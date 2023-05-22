## Live Standings Dashboard

Welcome to the Live Standings Dashboard! This web-based dashboard allows you to display live standings, team logos, and statistics for sports or Esports events. The data is pulled from a Google Sheets spreadsheet and updated in real-time.

![WebApp](https://cdn.discordapp.com/attachments/1110275710741917747/1110275753116971099/Pagina_exemplo.png)


### How to Use

1. **Fork the Repository**

   - Click on the "Fork" button in the top-right corner of this page.
   - This will create a copy of the repository in your GitHub account.

2. **Clone the Repository**

   - On your local machine, open the terminal or command prompt.
   - Clone the repository by running the following command:
   -  (Replace `<your-username>` with your GitHub username in the command below:)
     ```
     git clone https://github.com/your-username/Live-Standings-Dashboard.git
     ```

3. **Set Up Google Sheets API**

   - Go to the <a href="https://easy-data.mdbgo.io/" target="_blank">Easy Data documentation website</a>
   - Follow the documentation and tutorials provided to set up the Google Sheets API connection.
   - Make sure to obtain the necessary credentials and API key.

4. **Configure API Key and Spreadsheet ID**

   - In the cloned repository, open the `index.html` file in a text editor.
   - Locate the line that contains `const API_KEY = "YOUR_API_KEY";`.
   - Replace `YOUR_API_KEY` with your actual Google Sheets API key.
   - Locate the line that contains `const spreadsheetId = "YOUR_SPREADSHEET_ID";`.
   - Replace `YOUR_SPREADSHEET_ID` with the ID of your Google Sheets spreadsheet.

5. **Run the Live Server**

   - Open the project in your code editor (e.g., Visual Studio Code).
   - Install the Live Server extension if you haven't already.
   - Right-click on the `index.html` file and select "Open with Live Server".
   - This will launch the Live Standings Dashboard in your default browser.

6. **Access the Dashboard**

   - You can now view and interact with the Live Standings Dashboard locally.
   - The standings, team logos, and statistics will be updated in real-time based on the Google Sheets data.

7. **Customize and Deploy**

   - Feel free to customize the dashboard's design, layout, and functionality to suit your needs.
   - Once you're satisfied, you can deploy the Live Standings Dashboard to a web server or hosting platform of your choice.

**Note:** Don't forget to update the `YOUR_API_KEY` and `YOUR_SPREADSHEET_ID` placeholders with your actual Google Sheets API key and spreadsheet ID.

For an example spreadsheet that you can use, you can access it through this link: [Example Spreadsheet](https://docs.google.com/spreadsheets/d/1Zw8CCSHD4xBwiZEopKtlGXEQvByvvGnM8WF5AfpU84c)

Please refer to the [Easy Data documentation](https://easy-data.mdbgo.io/) for more details on usage and features.

Enjoy using the Live Standings Dashboard and have fun with your sports or Esports!

If you have any questions or need further assistance, feel free to reach out.

<h3 align="center">Support / contact :</h3>
<div align="center">
  <a href="https://twitter.com/arron_on" target="blank">
    <img src="https://img.shields.io/twitter/follow/arron_on?logo=twitter&style=for-the-badge" alt="arron_on">
  </a>
  <br>
  <a href="https://www.buymeacoffee.com/Arron0n">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="50" width="210">
  </a>
</div>

## Future Updates and Real-Time Data

Please note that the current version of the Live Standings Dashboard requires manual refresh by reloading the page (using F5) to update the data. However, in the future, I plan to implement real-time data updates. If you make any improvements or additions to the project and would like to contribute, please feel free to submit a pull request. I will review and consider integrating the changes into the main project.
