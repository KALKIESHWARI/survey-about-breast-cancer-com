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
            <label for="Age">Age</label>
            <input type="number" name="Age" id="Age" class="formControl" placeholder="Enter your Age" required>
        </div>

        <!-- Gender section -->
        <div class="form-group">
            <label for="Gender">Gender</label>
            <input type="text" name="Gender" id="Gender" class="formControl" placeholder="Enter your Gender" required>
        </div>

        <!-- Email section -->
        <div class="form-group">
            <label for="email">Email</label>
            <input type="email" name="email" id="email" class="formControl" placeholder="Enter your email">
        </div>

        <!-- Radio button sections -->
        <div class="form-group">
            <p>Do you know the importance of regular breast checkup?</p>
            <label><input type="radio" name="importance" value="Yes" class="inputRadio" checked> Yes</label>
            <label><input type="radio" name="importance" value="No" class="inputRadio"> No</label>
        </div>

        <div class="form-group">
            <p>Have you ever attended a breast health awareness program?</p>
            <label><input type="radio" name="awareness" value="Yes" class="inputRadio" checked> Yes</label>
            <label><input type="radio" name="awareness" value="No" class="inputRadio"> No</label>
        </div>

        <div class="form-group">
            <p>Have you undergone any breast surgeries or treatment?</p>
            <label><input type="radio" name="surgeries" value="Yes" class="inputRadio" checked> Yes</label>
            <label><input type="radio" name="surgeries" value="No" class="inputRadio"> No</label>
            <div class="form-group">
                <textarea name="surgery-details" cols="30" rows="5" class="textarea" placeholder="If Yes, please specify..."></textarea>
            </div>
        </div>

        <div class="form-group">
            <p>Do you know the signs and symptoms of breast cancer?</p>
            <label><input type="radio" name="symptoms" value="Yes" class="inputRadio" checked> Yes</label>
            <label><input type="radio" name="symptoms" value="No" class="inputRadio"> No</label>
        </div>

        <div class="form-group">
            <p>BREAST SELF-EXAMINATION (BSE)</p>
            <p>BSE is a monthly self-check for breast changes, using a mirror and hands to inspect and feel for lumps, thickening, or unusual changes in breast tissue.</p>
        </div>

        <div class="form-group">
            <p>Do you perform regular BSE?</p>
            <label><input type="radio" name="perform-bse" value="Yes" class="inputRadio" checked> Yes</label>
            <label><input type="radio" name="perform-bse" value="No" class="inputRadio"> No</label>
        </div>

        <div class="form-group">
            <p>What age did you start performing BSE?</p>
            <textarea name="start-age" cols="30" rows="1" class="textarea" placeholder="Please specify..."></textarea>
        </div>

        <div class="form-group">
            <p>How often do you perform BSE?</p>
            <label><input type="radio" name="frequency-bse" value="Once in a month" class="inputRadio" checked> Once in a month</label>
            <label><input type="radio" name="frequency-bse" value="Twice in a month" class="inputRadio"> Twice in a month</label>
            <label><input type="radio" name="frequency-bse" value="Two months once" class="inputRadio"> Two months once</label>
        </div>

        <div class="form-group">
            <p>Have you noticed any changes in your breast during BSE?</p>
            <label><input type="radio" name="changes-bse" value="Yes" class="inputRadio" checked> Yes</label>
            <label><input type="radio" name="changes-bse" value="No" class="inputRadio"> No</label>
        </div>

        <div class="form-group">
            <p>CLINICAL BREAST EXAMINATION (CBE)</p>
            <p>CBE is a healthcare professional visually inspects and palpates the breasts to detect abnormalities, such as lumps, thickening, or nipple discharge, typically done annually for women over 40.</p>
        </div>

        <div class="form-group">
            <p>Have you ever heard about CBE?</p>
            <label><input type="radio" name="heard-cbe" value="Yes" class="inputRadio" checked> Yes</label>
            <label><input type="radio" name="heard-cbe" value="No" class="inputRadio"> No</label>
        </div>

        <div class="form-group">
            <p>Have you ever had a CBE by a healthcare professional?</p>
            <label><input type="radio" name="had-cbe" value="Yes" class="inputRadio" checked> Yes</label>
            <label><input type="radio" name="had-cbe" value="No" class="inputRadio"> No</label>
        </div>

        <div class="form-group">
            <p>How often do you get CBE?</p>
            <textarea name="frequency-cbe" cols="30" rows="1" class="textarea" placeholder="Please specify..."></textarea>
        </div>

        <div class="form-group">
            <p>Have any abnormalities been detected during CBE?</p>
            <label><input type="radio" name="abnormalities-cbe" value="Yes" class="inputRadio" checked> Yes</label>
            <label><input type="radio" name="abnormalities-cbe" value="No" class="inputRadio"> No</label>
        </div>

        <div class="form-group">
            <p>MAMMOGRAPHY</p>
            <p>A low-dose X-ray exam that produces detailed breast images, helping detect cancer, cysts, or tumors, typically recommended annually for women over 40.</p>
        </div>

        <div class="form-group">
            <p>Have you ever had a mammogram?</p>
            <label><input type="radio" name="had-mammogram" value="Yes" class="inputRadio" checked> Yes</label>
            <label><input type="radio" name="had-mammogram" value="No" class="inputRadio"> No</label>
        </div>

        <div class="form-group">
            <p>Have you had a mammogram in the past year?</p>
            <label><input type="radio" name="mammogram-year" value="Yes" class="inputRadio" checked> Yes</label>
            <label><input type="radio" name="mammogram-year" value="No" class="inputRadio"> No</label>
            <div class="form-group">
                <textarea name="mammogram-details" cols="30" rows="2" class="textarea" placeholder="If Yes, please specify..."></textarea>
            </div>
        </div>

        <div class="form-group">
            <p>Have any abnormalities been detected during mammography?</p>
            <label><input type="radio" name="abnormalities-mammography" value="Yes" class="inputRadio" checked> Yes</label>
            <label><input type="radio" name="abnormalities-mammography" value="No" class="inputRadio"> No</label>
        </div>

        <!-- Feedback section -->
        <div class="form-group">
            <p>Give us your feedback</p>
            <textarea name="feedback" cols="30" rows="5" id="feedback" class="textarea" placeholder="Enter your feedback here..."></textarea>
        </div>

        <!-- Submit button -->
        <div class="form-group">
            <button type="submit" id="submit" class="btn">Submit</button>
        </div>
    </form>
</div>
</body>
</html>
