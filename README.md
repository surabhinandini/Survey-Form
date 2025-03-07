<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey Form</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1 id="title">Survey Form</h1>
    <p id="description">Please fill out this survey to help us improve our services.</p>
    
    <form id="survey-form">
        <label id="name-label" for="name">Name:</label>
        <input id="name" type="text" placeholder="Enter your name" required>
        
        <label id="email-label" for="email">Email:</label>
        <input id="email" type="email" placeholder="Enter your email" required>
        
        <label id="number-label" for="number">Age:</label>
        <input id="number" type="number" placeholder="Enter your age" min="18" max="99" required>
        
        <label for="dropdown">Select your occupation:</label>
        <select id="dropdown">
            <option value="student">Student</option>
            <option value="professional">Professional</option>
        </select>
        
        <fieldset>
            <legend>Would you recommend us?</legend>
            <label><input type="radio" name="recommend" value="yes"> Yes</label>
            <label><input type="radio" name="recommend" value="no"> No</label>
        </fieldset>
        
        <fieldset>
            <legend>What features do you like? (Check all that apply)</legend>
            <label><input type="checkbox" value="design"> Design</label>
            <label><input type="checkbox" value="usability"> Usability</label>
            <label><input type="checkbox" value="performance"> Performance</label>
        </fieldset>
        
        <label for="comments">Additional Comments:</label>
        <textarea id="comments" placeholder="Enter your comments here..."></textarea>
        
        <button id="submit" type="submit">Submit</button>
    </form>
</body>
</html>

                            
