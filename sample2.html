<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Verb To Be Trivia</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .question {
            font-size: 20px;
            margin-bottom: 15px;
        }
        .options button {
            display: block;
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            background-color: #007bff;
            color: white;
            font-size: 16px;
        }
        .options button.correct {
            background-color: #28a745;
        }
        .options button.incorrect {
            background-color: #dc3545;
        }
        .next-btn {
            margin-top: 10px;
            padding: 10px 20px;
            font-size: 16px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            display: none;
        }
    </style>
</head>
<body>
    <div class="container animate__animated animate__fadeIn">
        <h1>Verb To Be Trivia</h1>
        <p class="question" id="question"></p>
        <div class="options" id="options"></div>
        <button class="next-btn" id="next" onclick="nextQuestion()">Next</button>
        <p id="score" style="display: none;"></p>
    </div>
    
    <script>
        const questions = [
            { q: "Choose the correct sentence:", a: ["She am a doctor.", "She is a doctor.", "She are a doctor.", "She be a doctor."], correct: 1 },
            { q: "Choose the correct sentence:", a: ["They is happy.", "They am happy.", "They are happy.", "They be happy."], correct: 2 },
            { q: "Which is correct?", a: ["I is a teacher.", "I are a teacher.", "I am a teacher.", "I be a teacher."], correct: 2 },
            { q: "Fill in the blank: He ___ a student.", a: ["am", "is", "are", "be"], correct: 1 },
            { q: "Choose the correct sentence:", a: ["You is my friend.", "You am my friend.", "You are my friend.", "You be my friend."], correct: 2 },
            { q: "Fill in the blank: It ___ a sunny day.", a: ["am", "is", "are", "be"], correct: 1 },
            { q: "Choose the correct sentence:", a: ["We is from Mexico.", "We am from Mexico.", "We are from Mexico.", "We be from Mexico."], correct: 2 },
            { q: "Which is correct?", a: ["They am tired.", "They is tired.", "They are tired.", "They be tired."], correct: 2 },
            { q: "Fill in the blank: I ___ a student.", a: ["am", "is", "are", "be"], correct: 0 },
            { q: "Choose the correct sentence:", a: ["She am beautiful.", "She is beautiful.", "She are beautiful.", "She be beautiful."], correct: 1 }
        ];
        
        let currentQuestion = 0;
        let score = 0;
        
        function loadQuestion() {
            const q = questions[currentQuestion];
            document.getElementById('question').textContent = q.q;
            const optionsContainer = document.getElementById('options');
            optionsContainer.innerHTML = '';
            
            q.a.forEach((option, index) => {
                const btn = document.createElement('button');
                btn.textContent = option;
                btn.onclick = () => checkAnswer(index, btn);
                optionsContainer.appendChild(btn);
            });
            
            document.getElementById('next').style.display = 'none';
        }
        
        function checkAnswer(selectedIndex, btn) {
            const correctIndex = questions[currentQuestion].correct;
            const buttons = document.querySelectorAll('.options button');
            buttons.forEach(b => b.disabled = true);
            
            if (selectedIndex === correctIndex) {
                btn.classList.add('correct');
                score++;
            } else {
                btn.classList.add('incorrect');
                buttons[correctIndex].classList.add('correct');
            }
            
            document.getElementById('next').style.display = 'block';
        }
        
        function nextQuestion() {
            currentQuestion++;
            if (currentQuestion < questions.length) {
                loadQuestion();
            } else {
                showScore();
            }
        }
        
        function showScore() {
            document.querySelector('.container').innerHTML = `
                <h1>Results</h1>
                <p>You got ${score} out of ${questions.length} correct.</p>
                <p>${getFeedback(score)}</p>
            `;
        }
        
        function getFeedback(score) {
            if (score === 10) return "Excellent! You mastered the verb To Be.";
            if (score >= 7) return "Great job! Keep practicing.";
            if (score >= 4) return "Good effort, but you can improve.";
            return "Keep studying, you can do better!";
        }
        
        loadQuestion();
    </script>
</body>
</html>
