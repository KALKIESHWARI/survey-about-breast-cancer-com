<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="form.css">
    <title>Survey Form</title>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1 id="title">STUDY ABOUT BREAST CANCER</h1>
            <p id="description">This survey aims to gather information about your breast health checkup.</p>
        </header>
        <form action="" id="survey-form">
            <!-- Text section -->
            <div class="form-group">
                <label for="name">Name</label>
                <input type="text" name="name" id="name" class="formControl" placeholder="Enter your name" required>
            </div>
            <!-- Age section -->
            <div class="form-group">
                <label for="age">Age</label>
                <input type="number" name="age" id="age" class="formControl" placeholder="Enter your age" required>
            </div>
            <!-- Gender section -->
            <div class="form-group">
                <label for="gender">Gender</label>
                <input type="text" name="gender" id="gender" class="formControl" placeholder="Enter your gender" required>
            </div>
            <!-- Email section -->
            <div class="form-group">
                <label for="email">Email</label> 
                <input type="email" name="email" id="email" class="formControl" placeholder="Enter your email">
            </div>

            <!-- Survey Questions -->
            <div class="form-group">
                <p>Do you know the importance of regular breast checkup?</p>
                <label>
                    <input type="radio" name="know_importance" value="Yes" class="inputRadio" checked> Yes
                </label>
                <label>
                    <input type="radio" name="know_importance" value="No" class="inputRadio"> No
                </label>
            </div>

            <div class="form-group">
                <p>Have you ever attended a breast health awareness program?</p>
                <label>
                    <input type="radio" name="attended_awareness" value="Yes" class="inputRadio" checked> Yes
                </label>
                <label>
                    <input type="radio" name="attended_awareness" value="No" class="inputRadio"> No
                </label>
            </div>

            <!-- Breast Surgery or Treatment -->
            <div class="form-group">
                <p>Have you undergone any breast surgeries or treatment?</p>
                <label>
                    <input type="radio" name="undergone_surgery" value="Yes" class="inputRadio" checked> Yes
                </label>
                <label>
                    <input type="radio" name="undergone_surgery" value="No" class="inputRadio"> No
                </label>
                <div class="form-group" id="ifYesSpecify">
                    <textarea name="surgery_details" cols="30" rows="5" class="textarea" placeholder="Please specify..."></textarea>
                </div>
            </div>

            <!-- Additional Questions... -->

            <!-- Feedback Section -->
            <div class="form-group">
                <p>Give us your feedback</p>
                <textarea name="feedback" cols="30" rows="5" id="feedback" class="textarea" placeholder="Enter your feedback here..."></textarea>
            </div>

            <div class="form-group">
                <button type="submit" id="submit" class="btn">Submit</button>
            </div>
        </form>
    </div>
</body>
</html>

