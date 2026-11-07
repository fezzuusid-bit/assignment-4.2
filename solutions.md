<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Job Application Form</title>
</head>
<body>
    <main>
        <h1>Job Application Form</h1>
        <form action="#" method="POST">
            <div>
                <label for="fullname">Full Name:</label>
                <input type="text" id="fullname" name="fullname" required>
            </div>

            <div>
                <label for="email">Email Address:</label>
                <input type="email" id="email" name="email" required>
            </div>

            <div>
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required>
            </div>

            <div>
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required>
            </div>

            <div>
                <label for="portfolio">Portfolio URL:</label>
                <input type="url" id="portfolio" name="portfolio" placeholder="https://example.com" required>
            </div>

            <fieldset>
                <legend>Preferred Shift:</legend>
                <input type="radio" id="shift-day" name="shift" value="day" required>
                <label for="shift-day">Day</label>
                <input type="radio" id="shift-night" name="shift" value="night">
                <label for="shift-night">Night</label>
            </fieldset>

            <fieldset>
                <legend>Skills:</legend>
                <input type="checkbox" id="skill-html" name="skills" value="html">
                <label for="skill-html">HTML</label>
                <input type="checkbox" id="skill-css" name="skills" value="css">
                <label for="skill-css">CSS</label>
                <input type="checkbox" id="skill-javascript" name="skills" value="javascript">
                <label for="skill-javascript">JavaScript</label>
                <input type="checkbox" id="skill-java" name="skills" value="java">
                <label for="skill-java">Java</label>
            </fieldset>

            <div>
                <label for="role">Job Role:</label>
                <select id="role" name="role" required>
                    <option value="">-- Select a Role --</option>
                    <option value="frontend">Frontend Developer</option>
                    <option value="backend">Backend Developer</option>
                    <option value="fullstack">Full Stack Developer</option>
                </select>
            </div>

            <div>
                <label for="application-id">Application ID (Auto-generated):</label>
                <input type="text" id="application-id" name="application_id" value="APP-2026-8941" disabled>
            </div>

            <div>
                <label for="cover-letter">Cover Letter:</label>
                <textarea id="cover-letter" name="cover_letter" rows="5" cols="40" placeholder