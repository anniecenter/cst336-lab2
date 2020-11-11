<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>US Quiz</title>
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/underscore.js/1.9.1/underscore-min.js"></script>
        <script>
            $(document).ready(function() {
                // Global Variables
                var score = 0;
                var attempts = localStorage.getItem("total_attempts");
                
                // Event Listeners
                $("button").on("click", gradeQuiz);
                $(".q5Choice").on("click", function() {
                   $(".q5Choice").css("background","");
                   $(this).css("background","rgb(255, 255, 0)");
                });
                
                displayQ4Choices();
                
                function displayQ4Choices() {
                    let q4ChoicesArray = ["Maine", "Rhode Island", "Maryland", "Delaware"];
                    q4ChoicesArray = _.shuffle(q4ChoicesArray);
                    
                    for(let i = 0; i < q4ChoicesArray.length; i++) {
                        $("#q4Choices").append(` <input type="radio" name="q4" id="${q4ChoicesArray[i]}"
                           value="${q4ChoicesArray[i]}"> <label for="${q4ChoicesArray[i]}"> ${
                           q4ChoicesArray[i]}</label>`);
                    }
                }
                
                displayQ9Choices();
                
                function displayQ9Choices() {
                    let q9ChoicesArray = ["New Mexico, Oklahoma, Louisiana, Arkansas", 
                                          "Kansas, New Mexico, Arkansas, Mississippi", 
                                          "Oklahoma, Louisiana, Missouri, New Mexico", 
                                          "Arkansas, Kansas, Oklahoma, Mississippi"];
                    q9ChoicesArray = _.shuffle(q9ChoicesArray);
                    
                    for(let i = 0; i < q9ChoicesArray.length; i++) {
                        $("#q9Choices").append(` <tr><td><input type="radio" name="q9" id="${q9ChoicesArray[i]}"
                           value="${q9ChoicesArray[i]}"> <label for="${q9ChoicesArray[i]}"> ${
                           q9ChoicesArray[i]}</label></tr></td>`);
                    }
                }
                
                // functions
                function isFormValid() {
                    let isValid = true;
                    if($("#q1").val() == "") {
                        isValid = false;
                        $("#validationFdbk").html("Question 1 was not answered");
                    }
                    else if($("#q2").val() == "") {
                        isValid = false;
                        $("#validationFdbk").html("Question 2 was not answered");
                    }
                    else if(!$("#Jefferson").is(":checked") && !$("#Roosevelt").is(":checked")
                        && !$("#Jackson").is(":checked") && !$("#Franklin").is(":checked")) {
                        isValid = false;
                        $("#validationFdbk").html("Question 3 was not answered");
                    }
                    else if(!$("input[name=q4]:checked").val()) {
                        isValid = false;
                        $("#validationFdbk").html("Question 4 was not answered");
                    }
                    else if(!($("#seal1").css("background-color") == "rgb(255, 255, 0)") &&
                            !($("#seal2").css("background-color") == "rgb(255, 255, 0)") &&
                            !($("#seal3").css("background-color") == "rgb(255, 255, 0)")) {
                        isValid = false;
                        $("#validationFdbk").html("Question 5 was not answered");
                    }
                    else {
                        return isValid;
                    }
                }
                
                function rightAnswer(index) {
                    $(`#q${index}Feedback`).html("Correct!");
                    $(`#q${index}Feedback`).attr("class", "bg-success text-white");
                    $(`#markImg${index}`).html("<img src='img/checkmark.png' alt='checkmark'>");
                    score += 10;
                }
                
                function wrongAnswer(index) {
                    $(`#q${index}Feedback`).html("Incorrect!");
                    $(`#q${index}Feedback`).attr("class", "bg-warning text-white");
                    $(`#markImg${index}`).html("<img src='img/xmark.png' alt='xmark'>");
                }
                
                function gradeQuiz() {
                    $("#validationFdbk").html(""); // resets validation feedback
                    
                    if(!isFormValid()) {
                        return;
                    }
                    
                    // variables
                    score = 0;
                    let q1Response = $("#q1").val().toLowerCase();
                    let q2Response = $("#q2").val();
                    let q4Response = $("input[name=q4]:checked").val();
                    let q6Response = $("#q6").val().toLowerCase();
                    let q7Response = $("#q7").val();
                    let q9Response = $("input[name=q9]:checked").val();
                    let q10Response = $("#q10").val().toLowerCase();
                    
                    // Question 1
                    if(q1Response == "sacramento") {
                        rightAnswer(1);
                    }
                    else {
                       wrongAnswer(1);
                    }
                    // Question 2
                    if(q2Response == "mo") {
                        rightAnswer(2);
                    }
                    else {
                        wrongAnswer(2);
                    }
                    // Question 3
                    if($("#Jefferson").is(":checked") && $("#Roosevelt").is(":checked")
                        && !$("#Jackson").is(":checked") && !$("#Franklin").is(":checked")) {
                        rightAnswer(3);
                    }
                    else {
                        wrongAnswer(3);
                    }
                    // Question 4
                    if(q4Response == "Rhode Island") {
                        rightAnswer(4);
                    }
                    else {
                        wrongAnswer(4);
                    }
                    // Question 5
                    if($("#seal2").css("background-color") == "rgb(255, 255, 0)") {
                        rightAnswer(5);
                    }
                    else {
                        wrongAnswer(5);
                    }
                    // Question 6
                    if(q6Response == "new jersey") {
                        rightAnswer(6);
                    }
                    else {
                       wrongAnswer(6);
                    }
                    // Question 7
                    if(q7Response == "wy") {
                        rightAnswer(7);
                    }
                    else {
                        wrongAnswer(7);
                    }
                    // Question 8
                    if($("#or").is(":checked") && !$("#wa").is(":checked")
                        && $("#nv").is(":checked") && $("#az").is(":checked")) {
                        rightAnswer(8);
                    }
                    else {
                        wrongAnswer(8);
                    }
                    // Question 9
                    if(q9Response == "New Mexico, Oklahoma, Louisiana, Arkansas") {
                        rightAnswer(9);
                    }
                    else {
                        wrongAnswer(9);
                    }
                    // Question 10
                    if(q10Response == "washington dc" || q10Response == "washington d.c.") {
                        rightAnswer(10);
                    }
                    else {
                       wrongAnswer(10);
                    }
                    
                    // Scoring
                    if (score < 80) {
                        $("#totalScore").html(`Total Score: ${score}`);
                        $("#totalScore").attr("class","text-danger");
                    }
                    else {
                        $("#totalScore").html(`Total Score: ${score}`);
                        $("#totalScore").attr("class","text-success");
                        $("#validationFdbk").attr("class","bg-success text-white");
                        $("#validationFdbk").html("Wow! That's a great score!");
                    }
                    $("#totalAttempts").html(`Total Attempts: ${++attempts}`);
                    localStorage.setItem("total_attempts", attempts);
                }
            });//ready
        </script>
    </head>
    <body  class="text-center">
        <h1 class="jumbotron">US Geography Quiz</h1>
        <!-- Question 1 -->
        <h3><span id="markImg1"></span>What is the capital of California?</h3>
        <input type="text" id="q1">
        <br><br>
        <div id="q1Feedback"></div>
        <br>
        <!-- Question 2 -->
        <h3><span id="markImg2"></span>What is the longest river?</h3>
        <select id="q2">
            <option value="">Select One</option>
            <option value="ms">Mississippi</option>
            <option value="mo">Missouri</option>
            <option value="co">Colorado</option>
            <option value="de">Delaware</option>
        </select>
        <br><br>
        <div id="q2Feedback"></div>
        <br>
        <!-- Question 3 -->
        <h3><span id="markImg3"></span>Which Presidents are carved into Mt. Rushmore?</h3>
        <input type="checkbox" id="Jackson"> <label for="Jackson">A. Jackson</label>
        <input type="checkbox" id="Franklin"> <label for="Franklin">B. Franklin</label>
        <input type="checkbox" id="Jefferson"> <label for="Jefferson">T. Jefferson</label>
        <input type="checkbox" id="Roosevelt"> <label for="Roosevelt">T. Roosevelt</label>
        <br><br>
        <div id="q3Feedback"></div>
        <br>
        <!-- Question 4 -->
        <h3><span id="markImg4"></span>What is the smallest US state?</h3>
        <div id="q4Choices"></div>
        <br>
        <div id="q4Feedback"></div>
        <br>
        <!-- Question 5 -->
        <h3><span id="markImg5"></span>Which image is in the Great Seal of the State of California?</h3>
        <img src="img/seal1.png" alt="Seal 1" class="q5Choice" id="seal1">
        <img src="img/seal2.png" alt="Seal 2" class="q5Choice" id="seal2">
        <img src="img/seal3.png" alt="Seal 3" class="q5Choice" id="seal3">
        <br></br>
        <div id="q5Feedback"></div>
        </br>
        <!-- Question 6 -->
        <h3><span id="markImg6"></span>What state is the Statue of Liberty in?</h3>
        <input type="text" id="q6">
        <br><br>
        <div id="q6Feedback"></div>
        <br>
        <!-- Question 7 -->
        <h3><span id="markImg7"></span>What is the least populated state?</h3>
        <select id="q7">
            <option value="">Select One</option>
            <option value="ri">Rhode Island</option>
            <option value="ct">Connecticut</option>
            <option value="wy">Wyoming</option>
            <option value="de">Delaware</option>
        </select>
        <br><br>
        <div id="q7Feedback"></div>
        <br>
        <!-- Question 8 -->
        <h3><span id="markImg8"></span>Which states border California?</h3>
        <table class="table">
            <tr><td><input type="checkbox" id="or"> <label for="or">Oregon</label></td></tr>
            <tr><td><input type="checkbox" id="wa"> <label for="wa">Washington</label></td></tr>
            <tr><td><input type="checkbox" id="nv"> <label for="nv">Nevada</label></td></tr>
            <tr><td><input type="checkbox" id="az"> <label for="az">Arizona</label></td></tr>
        </table>
        <div id="q8Feedback"></div>
        <br>
        <!-- Question 9 -->
        <h3><span id="markImg9"></span>Which states border Texas?</h3>
        <table class="table" id="q9Choices"></table>
        <br>
        <div id="q9Feedback"></div>
        <br>
        <!-- Question 10 -->
        <h3><span id="markImg10"></span>What is the capital of the US?</h3>
        <input type="text" id="q10">
        <br><br>
        <div id="q10Feedback"></div>
        <br>
        <!-- Validation Feedback -->
        <h3 id="validationFdbk" class='bg-danger text-white'></h3>
        <br>
        <button class="btn btn-outline-success">Submit Quiz</button>
        <br></br>
        <!-- Total Score -->
        <h2 id="totalScore" class="text-info"></h2>
        <!-- Total Attempts -->
        <h3 id="totalAttempts"></h3>
    </body>
</html>
