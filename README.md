<!DOCTYPE html>
<html lang="en">
    <head>
    <title>Survey Form</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1 id="title">Survey Form</h1>
    <p id="description">Please fill out the survey form below:</p>
    <form id="survey-form">
      <label for="name" id="name-label">Name:</label>
      <input type="text" id="name" placeholder="Enter your name">
      <br>
      <label for="email" id="email-label">Email:</label>
      <input type="email" id="email" placeholder="Enter your email">
      <br>
      <label for="number" id="number-label">Number:</label>
      <input type="number" id="number" min="1" max="100" placeholder="Enter a number between 1 and 100">
      <br>
      <label for="dropdown" id="dropdown-label">Select an option:</label>
      <select id="dropdown">
        <option value="option1">Option 1</option>
        <option value="option2">Option 2</option>
      </select>
      <br>
      <label id="radio-label">Select a radio button:</label>
      <br>
      <input type="radio" name="radio-group" value="radio1">Radio 1
      <input type="radio" name="radio-group" value="radio2">Radio 2
      <br>
      <label id="checkbox-label">Select one or more checkboxes:</label>
      <br>
      <input type="checkbox" value="checkbox1">Checkbox 1
      <input type="checkbox" value="checkbox2">Checkbox 2
      <input type="checkbox" value="checkbox3">Checkbox 3
      <br>
      <label for="comments" id="comments-label">Additional Comments:</label>
      <br>
      <textarea id="comments"></textarea>
      <br>
      <button id="submit">Submit</button>
      </form>
      </body>
</html>
