# Abomosu-
Enrolment form
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abomosu Stem Senior High</title>

<style>

/* Color Variables */
:root {
    --sceptor-red: #b11226;
    --cream-peach: #ffe5d4;
    --light-peach: #fff3eb;
}

/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

/* Body Styling */
body {
    background: var(--cream-peach);
    color: #333;
    animation: fadeIn 1.5s ease-in-out;
}

/* Header */
header {
    background: var(--sceptor-red);
    color: white;
    text-align: center;
    padding: 30px;
    animation: slideDown 1s ease-out;
}

header h1 {
    font-size: 36px;
    letter-spacing: 1px;
}

/* Sections */
section {
    padding: 40px 20px;
    max-width: 900px;
    margin: auto;
    animation: fadeUp 1.2s ease-in-out;
}

/* Headings */
h2 {
    color: var(--sceptor-red);
    margin-bottom: 15px;
    border-bottom: 3px solid var(--sceptor-red);
    display: inline-block;
    padding-bottom: 5px;
}

/* Program List */
.programs p {
    background: var(--light-peach);
    padding: 10px;
    margin: 8px 0;
    border-left: 5px solid var(--sceptor-red);
    transition: transform 0.3s ease;
}

.programs p:hover {
    transform: translateX(10px);
}

/* Form Styling */
form {
    background: white;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    animation: fadeUp 1.5s ease-in-out;
}

form p {
    margin-top: 15px;
    font-weight: bold;
}

input {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    border-radius: 5px;
    border: 2px solid var(--sceptor-red);
    outline: none;
    transition: 0.3s;
}

input:focus {
    border-color: #ff6b6b;
    box-shadow: 0 0 8px rgba(177, 18, 38, 0.4);
}

/* Thank You */
.thankyou {
    text-align: center;
    color: var(--sceptor-red);
    margin-top: 20px;
    font-weight: bold;
    font-size: 18px;
}

/* Animations */
@keyframes fadeIn {
    from {opacity: 0;}
    to {opacity: 1;}
}

@keyframes slideDown {
    from {transform: translateY(-50px); opacity: 0;}
    to {transform: translateY(0); opacity: 1;}
}

@keyframes fadeUp {
    from {transform: translateY(30px); opacity: 0;}
    to {transform: translateY(0); opacity: 1;}
}

/* Responsive */
@media(max-width: 600px) {
    header h1 {
        font-size: 24px;
    }
}

</style>
</head>

<body>

<header>
    <h1>Abomosu Stem Senior High</h1>
</header>

<section>
    <p>
        Abomosu Stem Senior High is a senior high school in Abomosu town,
        located in the Eastern Region of Ghana.
    </p>
</section>

<section class="programs">
    <h2>Programmes In The School</h2>
    <p>• General Science</p>
    <p>• Biomedical Science</p>
    <p>• Computer Science</p>
    <p>• Robotics</p>
    <p>• Aviation and Aerospace</p>
</section>

<section>
    <h2>Online Application</h2>
    <h3>Note:</h3>
    <p>If you are a parent and you want your ward to continue his or her high school education here, please complete this form for enrollment.</p>

    <form>
        <p>Name of Father</p>
        <input type="text">

        <p>Name of Mother</p>
        <input type="text">

        <p>Occupation of Father</p>
        <input type="text">

        <p>Occupation of Mother</p>
        <input type="text">

        <p>Name of Ward</p>
        <input type="text">

        <p>Index Number of Ward</p>
        <input type="text">
    </form>

    <div class="thankyou">
        Thank You
    </div>
</section>

</body>
</html>
