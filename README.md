<!DOCTYPE html>
<html>
<head>
    <title>Home Workout Hub</title>

    <style>
        body {
            font-family: Arial;
        }

        nav button {
            margin: 5px;
            padding: 8px 12px;
            cursor: pointer;
        }

        section {
            display: none;
        }

        section.active {
            display: block;
        }
    </style>

    <script>
        function showSection(sectionId) {
            let sections = document.querySelectorAll("section");

            sections.forEach(sec => {
                sec.classList.remove("active");
            });

            document.getElementById(sectionId).classList.add("active");
        }

        window.onload = function() {
            showSection("home"); // default page
        }
    </script>
</head>

<body>

<header>
    <h2>Home Workout Hub</h2>

    <nav>
        <button onclick="showSection('home')">Home</button>
        <button onclick="showSection('workouts')">Workouts</button>
    </nav>

    <hr>
</header>

<!-- ================= HOME ================= -->
<section id="home">

    <h1>Welcome to Home Workout Hub</h1>
    <p>Your journey to a stronger and healthier body starts at home!</p>

    <h2>READ ME</h2>

    <img src="https://images.unsplash.com/photo-1554284126-aa88f22d8b74?auto=format&fit=crop&w=600&q=60" width="300">
    <p><b>"one day or day one?"</b></p>

    <br>

    <img src="https://images.unsplash.com/photo-1583454110551-21f2fa2afe61?auto=format&fit=crop&w=600&q=60" width="300">
    <p><b>"If you don't sacrifice for what you want, what you want becomes the sacrifice."</b></p>

    <br>

    <img src="https://images.unsplash.com/photo-1517960413843-0aee8e2b3285?auto=format&fit=crop&w=600&q=60" width="300">
    <p><b>"Not every lion that chased the deer caught it. But every lion that caught a deer chased it."</b></p>

    <br>

    <h2>Why Choose Home Workout?</h2>
    <ul>
        <li>No equipment needed</li>
        <li>Save money</li>
        <li>Save time</li>
        <li>Workout anytime</li>
    </ul>

</section>

<!-- ================= WORKOUTS ================= -->
<section id="workouts">

<h1>Workout Programs</h1>
<p>Select a difficulty level and start training!</p>

<hr>

<h2>🟢 Easy Level</h2>

<h3>Jumping Jacks</h3>
<p><b>Duration:</b> 3 sets of 20 reps</p>
<p><b>Benefit:</b> Improves cardiovascular endurance and warms up the body.</p>
<p>
<a href="https://www.youtube.com/watch?v=c4DAnQ6DtF8" target="_blank">Watch Here</a>
</p>

<h3>Wall Sit</h3>
<p><b>Duration:</b> 3 sets of 30 seconds</p>
<p><b>Benefit:</b> Strengthens legs and improves lower body endurance.</p>
<p>
<a href="https://www.youtube.com/watch?v=y-wV4Venusw" target="_blank">Watch Here</a>
</p>

<hr>

<h2>🟡 Intermediate Level</h2>

<h3>Push-ups</h3>
<p><b>Duration:</b> 3 sets of 10 reps</p>
<p><b>Benefit:</b> Builds chest, shoulders, and arm strength.</p>
<p>
<a href="https://www.youtube.com/watch?v=IODxDxX7oi4" target="_blank">Watch Here</a>
</p>

<h3>Bodyweight Squats</h3>
<p><b>Duration:</b> 3 sets of 15 reps</p>
<p><b>Benefit:</b> Strengthens legs, glutes, and improves mobility.</p>
<p>
<a href="https://www.youtube.com/watch?v=aclHkVaku9U" target="_blank">Watch Here</a>
</p>

<hr>

<h2>🔴 Hard Level</h2>

<h3>Burpees</h3>
<p><b>Duration:</b> 3 sets of 12 reps</p>
<p><b>Benefit:</b> Full-body workout that increases strength and endurance.</p>
<p>
<a href="https://www.youtube.com/watch?v=TU8QYVW0gDU" target="_blank">Watch Here</a>
</p>

<h3>Plank</h3>
<p><b>Duration:</b> 3 sets of 45 seconds</p>
<p><b>Benefit:</b> Strengthens core muscles and improves stability.</p>
<p>
<a href="https://www.youtube.com/watch?v=pSHjTRCQxIw" target="_blank">Watch Here</a>
</p>

</section>

<hr>

<footer>
    <p>© 2026 Home Workout Hub</p>
</footer>

</body>
</html>
