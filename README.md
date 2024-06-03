<html>
  <body>
    <h1>Investment Tracker App</h1>
    <p>This code is a simple investment tracker application that calculates the daily and total earnings of an investment over a period of 7 days.</p>
    <h2>How it works:</h2>
    <ol>
      <li>The user is prompted to enter the buying price per share.</li>
      <li>The user is then prompted to enter the closing price for each day of the week (7 days).</li>
      <li>For each day, the application calculates the earnings by subtracting the buying price from the closing price.</li>
      <li>The earnings are stored in an array <code>weekly</code>.</li>
      <li>The application then prints out a message indicating whether the investment has gained, lost, or broken even for each day.</li>
      <li>After all 7 days, the application calculates the total weekly earnings by summing up the earnings for each day.</li>
      <li>The total weekly earnings are printed out to the console.</li>
    </ol>
    <h2>Variables and Data Structures:</h2>
    <ul>
      <li><code>buyingPrice</code>: The buying price per share.</li>
      <li><code>closingPrice</code>: The closing price for each day.</li>
      <li><code>weekly</code>: An array of doubles to store the earnings for each day.</li>
      <li><code>day</code>: An integer variable to keep track of the current day.</li>
      <li><code>i</code>: An integer variable to iterate through the <code>weekly</code> array.</li>
      <li><code>j</code>: An integer variable to iterate through the <code>weekly</code> array in the second loop.</li>
      <li><code>totalWeeklyEarnings</code>: A double variable to store the total weekly earnings.</li>
    </ul>
    <h2>Methods:</h2>
    <ul>
      <li><code>Scanner</code> to read input from the user.</li>
      <li><code>System.out.println</code> and <code>System.out.printf</code> to print output to the console.</li>
      <li><code>Arrays</code> to store and manipulate the <code>weekly</code> array.</li>
    </ul>
  </body>
</html>

<b>Code Output On Console: </b>

![image](https://github.com/yusuftechx/investment-tracker-demo/assets/56741289/307e2db4-5ea2-4ce4-a617-2dad56c48b55)
