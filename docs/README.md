<html>
<head> 
    <style>
    body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        margin: 0;
        padding: 0;
        text-align: center;
    }

    h1 {
        background-color: #333;
        color: #fff;
        padding: 20px 0;
        margin: 0;
    }

    .container {
        max-width: 800px;
        margin: 0 auto;
        padding: 20px;
        background-color: #fff;
        border-radius: 5px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }

    .question {
        margin-bottom: 20px;
        text-align: left;
        padding: 10px;
        border: 1px solid #ccc;
        border-radius: 5px;
        background-color: #f9f9f9;
    }

    .options {
        margin-top: 10px;
    }

    label {
        display: block;
        margin-bottom: 10px;
    }

    input[type="radio"] {
        margin-right: 5px;
    }

    .button-container {
        text-align: center;
        margin-top: 20px;
    }

    button {
        background-color: #333;
        color: #fff;
        padding: 10px 20px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
    }

    .result-container {
        margin-top: 20px;
    }

    .incorrect {
        color: red;
    }
</style>
</head>
<body>
    <h1>PC Parts</h1>

    <div class="container">
        <div class="question">
            <p>Question 1: What component is responsible for long-term data storage in a computer?</p>
            <div class="options">
                <label><input type="radio" name="q1" value="a"> a. CPU</label>
                <label><input type="radio" name="q1" value="b"> b. RAM</label>
                <label><input type="radio" name="q1" value="c"> c. Hard drive *</label>
            </div>
        </div>

        <div class="question">
            <p>Question 2: Which of the following options best describes the function of a motherboard?</p>
            <div class="options">
                <label><input type="radio" name="q2" value="a"> a. Processes data and runs programs.</label>
                <label><input type="radio" name="q2" value="b"> b. Connects all computer components and facilitates communication between them. *</label>
                <label><input type="radio" name="q2" value="c"> c. Stores files and applications.</label>
            </div>
        </div>

        <div class="question">
            <p>Question 3: What device is essential for audio output on a computer?</p>
            <div class="options">
                <label><input type="radio" name="q3" value="a"> a. Monitor</label>
                <label><input type="radio" name="q3" value="b"> b. Speakers *</label>
                <label><input type="radio" name="q3" value="c"> c. Keyboard</label>
            </div>
        </div>

        <div class="question">
            <p>Question 4: What type of memory is used to store data and programs temporarily while the computer is powered on?</p>
            <div class="options">
                <label><input type="radio" name="q4" value="a"> a. Hard drive</label>
                <label><input type="radio" name="q4" value="b"> b. RAM *</label>
                <label><input type="radio" name="q4" value="c"> c. CPU</label>
            </div>
        </div>

        <div class="question">
            <p>Question 5: Which component is responsible for cooling the CPU in a computer?</p>
            <div class="options">
                <label><input type="radio" name="q5" value="a"> a. Power supply</label>
                <label><input type="radio" name="q5" value="b"> b. CPU fan *</label>
                <label><input type="radio" name="q5" value="c"> c. Hard drive</label>
            </div>
        </div>

        <div class="question">
            <p>Question 6: What part of the computer provides electrical power to all components?</p>
            <div class="options">
                <label><input type="radio" name="q6" value="a"> a. Motherboard</label>
                <label><input type="radio" name="q6" value="b"> b. Power supply unit *</label>
                <label><input type="radio" name="q6" value="c"> c. CPU</label>
            </div>
        </div>

        <div class="question">
            <p>Question 7: Which of the following options best describes the function of a graphics card?</p>
            <div class="options">
                <label><input type="radio" name="q7" value="a"> a. Stores graphic files.</label>
                <label><input type="radio" name="q7" value="b"> b. Processes complex mathematical calculations.</label>
                <label><input type="radio" name="q7" value="c"> c. Generates images on the screen and accelerates graphics in games and applications. *</label>
            </div>
        </div>

        <div class="question">
            <p>Question 8: What device is used to input data into a computer by moving it on a flat surface?</p>
            <div class="options">
                <label><input type="radio" name="q8" value="a"> a. Monitor</label>
                <label><input type="radio" name="q8" value="b"> b. Mouse *</label>
                <label><input type="radio" name="q8" value="c"> c. Keyboard</label>
            </div>
        </div>

        <div class="question">
            <p>Question 9: Which of the following components is typically a solid-state drive (SSD) or hard disk drive (HDD)?</p>
            <div class="options">
                <label><input type="radio" name="q9" value="a"> a. CPU</label>
                <label><input type="radio" name="q9" value="b"> b. RAM</label>
                <label><input type="radio" name="q9" value="c"> c. Data storage *</label>
            </div>
        </div>

        <div class="question">
            <p>Question 10: What type of memory is volatile and is erased when the computer is turned off?</p>
            <div class="options">
                <label><input type="radio" name="q10" value="a"> a. Hard drive</label>
                <label><input type="radio" name="q10" value="b"> b. RAM *</label>
                <label><input type="radio" name="q10" value="c"> c. CPU</label>
            </div>
        </div>

        <div class="question">
            <p>Question 11: What type of connector is used to attach peripherals like printers and cameras to a computer?</p>
            <div class="options">
                <label><input type="radio" name="q11" value="a"> a. USB *</label>
                <label><input type="radio" name="q11" value="b"> b. HDMI</label>
                <label><input type="radio" name="q11" value="c"> c. VGA</label>
            </div>
        </div>

        <div class="question">
            <p>Question 12: Which component is essential for displaying information on a computer?</p>
            <div class="options">
                <label><input type="radio" name="q12" value="a"> a. Sound card</label>
                <label><input type="radio" name="q12" value="b"> b. Motherboard</label>
                <label><input type="radio" name="q12" value="c"> c. Graphics card *</label>
            </div>
        </div>

        <div class="button-container">
            <button onclick="calculateScore()">Calculate Score</button>
        </div>

        <div class="result-container">
            <p id="score"></p>
            <p id="incorrectAnswers" class="incorrect"></p>
        </div>
    </div>

    <script>
        function calculateScore() {
            var score = 0;
            var answers = ["b", "b", "c", "b", "b", "c", "b", "c", "b", "b", "a", "c"];
            var userAnswers = [];

            for (var i = 1; i <= 12; i++) {
                var selection = document.querySelector('input[name="q' + i + '"]:checked');
                if (selection) {
                    userAnswers.push(selection.value);
                    if (selection.value === answers[i - 1]) {
                        score++;
                    }
                } else {
                    userAnswers.push("");
                }
            }

            var result = "Score: " + score + " out of 12 correct answers";
            document.getElementById("score").innerHTML = result;

            // Display incorrect answers
            var incorrectAnswers = [];
            for (var i = 0; i < answers.length; i++) {
                if (userAnswers[i] !== answers[i]) {
                    incorrectAnswers.push("Question " + (i + 1) + ": Your answer - " + userAnswers[i] + ", Correct answer - " + answers[i]);
                }
            }

            var incorrectAnswersText = incorrectAnswers.length > 0 ? "Incorrect Answers: " + incorrectAnswers.join(", ") : "All answers are correct";
            document.getElementById("incorrectAnswers").innerHTML = incorrectAnswersText;
        }
    </script>
</body>
</html>
