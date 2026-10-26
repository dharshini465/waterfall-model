```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Waterfall Model</title>

<style>

* {
    box-sizing: border-box;
}

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #eef6ff;
    color: #172033;
    line-height: 1.6;
}

/* HEADER */

header {
    background: linear-gradient(135deg, #1769aa, #4facfe);
    color: white;
    text-align: center;
    padding: 50px 20px;
}

header h1 {
    font-size: 42px;
    margin: 0;
}

header p {
    font-size: 18px;
    margin-top: 10px;
}

/* SECTIONS */

section {
    max-width: 900px;
    margin: 35px auto;
    padding: 0 20px;
}

.card {
    background: white;
    padding: 25px;
    border-radius: 18px;
    box-shadow: 0 5px 15px #cbd5e1;
}

h2 {
    color: #1769aa;
    margin-bottom: 18px;
}

/* ANIMATED WATERFALL DIAGRAM */

.diagram {
    background: white;
    padding: 25px;
    border-radius: 20px;
    box-shadow: 0 5px 15px #cbd5e1;
    text-align: center;
}

.water-step {
    display: flex;
    align-items: center;
    gap: 15px;
    text-align: left;
    background: #eef6ff;
    padding: 18px;
    margin: 10px auto;
    border-radius: 15px;
    border-left: 5px solid #1769aa;
    animation: slideIn 0.8s ease;
}

.number {
    min-width: 42px;
    height: 42px;
    background: #1769aa;
    color: white;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: bold;
}

.water-step h3 {
    margin: 0;
    color: #1769aa;
}

.water-step p {
    margin: 5px 0 0;
}

.diagram-arrow {
    font-size: 30px;
    color: #1769aa;
    animation: bounce 1.2s infinite;
}

@keyframes slideIn {
    from {
        opacity: 0;
        transform: translateY(25px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes bounce {
    50% {
        transform: translateY(6px);
    }
}

/* WATERFALL STAGES */

.stage {
    background: white;
    margin: 15px 0;
    padding: 20px;
    border-radius: 15px;
    border-left: 6px solid #1769aa;
    box-shadow: 0 4px 12px #d5deea;
}

.stage h3 {
    color: #1769aa;
    margin-top: 0;
}

.arrow {
    text-align: center;
    color: #1769aa;
    font-size: 28px;
}

/* INTERACTIVE WATERFALL */

.waterfall {
    background: white;
    padding: 25px;
    border-radius: 18px;
    box-shadow: 0 5px 15px #cbd5e1;
    text-align: center;
}

.flow button {
    display: block;
    width: 90%;
    margin: 10px auto;
    padding: 15px;
    border: none;
    border-radius: 12px;
    background: #1769aa;
    color: white;
    font-size: 16px;
    font-weight: bold;
}

.flow button:active {
    transform: scale(0.97);
}

.flow span {
    font-size: 25px;
    color: #1769aa;
}

#info {
    margin-top: 20px;
    padding: 18px;
    border-radius: 12px;
    background: #eef6ff;
    font-weight: bold;
}

/* OOP */

.oop {
    background: #172033;
    color: white;
    padding: 25px;
    border-radius: 18px;
}

.oop h2 {
    color: #4facfe;
}

.oop-card {
    background: white;
    color: #172033;
    padding: 18px;
    margin: 15px 0;
    border-radius: 12px;
    border-left: 5px solid #4facfe;
}

.oop-card h3 {
    color: #1769aa;
    margin-top: 0;
}

/* ADVANTAGES */

.pros-cons {
    margin-top: 35px;
}

.pros,
.cons {
    background: white;
    padding: 25px;
    margin: 20px 0;
    border-radius: 18px;
    box-shadow: 0 5px 15px #cbd5e1;
}

.pros {
    border-left: 6px solid #22c55e;
}

.cons {
    border-left: 6px solid #ef4444;
}

.pros h3 {
    color: #16a34a;
}

.cons h3 {
    color: #dc2626;
}

li {
    margin: 10px 0;
}

/* REAL WORLD */

.example {
    background: linear-gradient(135deg, #ffffff, #e8f4ff);
    padding: 25px;
    border-radius: 18px;
    box-shadow: 0 5px 15px #cbd5e1;
}

/* FOOTER */

footer {
    text-align: center;
    background: #1769aa;
    color: white;
    padding: 25px;
    margin-top: 45px;
}

</style>
</head>

<body>

<!-- HEADER -->

<header>

<h1>🌊 Waterfall Model</h1>

<p>
Object-Oriented Software Programming
</p>

</header>


<!-- INTRODUCTION -->

<section>

<div class="card">

<h2>What is the Waterfall Model?</h2>

<p>
The Waterfall Model is a software development model
where development happens step by step.
Each stage is completed before moving to the next stage.
</p>

<p>
It follows a sequential approach, similar to water
flowing downward from one level to another.
</p>

</div>

</section>


<!-- ANIMATED WATERFALL DIAGRAM -->

<section>

<div class="diagram">

<h2>🌊 Waterfall Flow</h2>

<div class="water-step">

<div class="number">1</div>

<div>

<h3>Requirements</h3>

<p>Collect and document user requirements.</p>

</div>

</div>

<div class="diagram-arrow">↓</div>


<div class="water-step">

<div class="number">2</div>

<div>

<h3>System Design</h3>

<p>Plan the structure and architecture.</p>

</div>

</div>

<div class="diagram-arrow">↓</div>


<div class="water-step">

<div class="number">3</div>

<div>

<h3>Implementation</h3>

<p>Write the actual software code.</p>

</div>

</div>

<div class="diagram-arrow">↓</div>


<div class="water-step">

<div class="number">4</div>

<div>

<h3>Testing</h3>

<p>Find and fix errors.</p>

</div>

</div>

<div class="diagram-arrow">↓</div>


<div class="water-step">

<div class="number">5</div>

<div>

<h3>Deployment</h3>

<p>Release the software to users.</p>

</div>

</div>

<div class="diagram-arrow">↓</div>


<div class="water-step">

<div class="number">6</div>

<div>

<h3>Maintenance</h3>

<p>Update and improve the software.</p>

</div>

</div>

</div>

</section>


<!-- STAGES -->

<section>

<h2>📋 Stages of Waterfall Model</h2>

<div class="stage">

<h3>1. Requirements</h3>

<p>
The development team collects and documents
the needs and requirements of the users.
</p>

</div>

<div class="arrow">↓</div>

<div class="stage">

<h3>2. System Design</h3>

<p>
The structure, architecture and design of
the software are planned.
</p>

</div>

<div class="arrow">↓</div>

<div class="stage">

<h3>3. Implementation</h3>

<p>
Programmers write the actual software code
according to the approved design.
</p>

</div>

<div class="arrow">↓</div>

<div class="stage">

<h3>4. Testing</h3>

<p>
The software is tested to find errors and
make sure it works correctly.
</p>

</div>

<div class="arrow">↓</div>

<div class="stage">

<h3>5. Deployment</h3>

<p>
The completed software is delivered and
made available to users.
</p>

</div>

<div class="arrow">↓</div>

<div class="stage">

<h3>6. Maintenance</h3>

<p>
The software is updated, corrected and
maintained after deployment.
</p>

</div>

</section>


<!-- INTERACTIVE WATERFALL -->

<section>

<div class="waterfall">

<h2>🔄 Interactive Waterfall Process</h2>

<p>
Tap a stage to learn more.
</p>

<div class="flow">

<button onclick="showInfo('requirements')">
1. Requirements
</button>

<span>↓</span>

<button onclick="showInfo('design')">
2. Design
</button>

<span>↓</span>

<button onclick="showInfo('implementation')">
3. Implementation
</button>

<span>↓</span>

<button onclick="showInfo('testing')">
4. Testing
</button>

<span>↓</span>

<button onclick="showInfo('deployment')">
5. Deployment
</button>

<span>↓</span>

<button onclick="showInfo('maintenance')">
6. Maintenance
</button>

</div>

<div id="info">

👆 Tap any stage above.

</div>

</div>

</section>


<!-- OOP -->

<section>

<div class="oop">

<h2>💻 OOP Concepts</h2>

<div class="oop-card">

<h3>Class</h3>

<p>
A class is a blueprint used to create objects.
</p>

</div>

<div class="oop-card">

<h3>Object</h3>

<p>
An object is an instance of a class.
</p>

</div>

<div class="oop-card">

<h3>Encapsulation</h3>

<p>
It combines data and methods into a single unit.
</p>

</div>

<div class="oop-card">

<h3>Inheritance</h3>

<p>
It allows one class to inherit properties
and methods from another class.
</p>

</div>

<div class="oop-card">

<h3>Polymorphism</h3>

<p>
It allows the same method to behave differently
in different situations.
</p>

</div>

<div class="oop-card">

<h3>Abstraction</h3>

<p>
It hides unnecessary details and shows only
important features.
</p>

</div>

</div>

</section>


<!-- OOP CONNECTION -->

<section>

<div class="card">

<h2>🔗 Waterfall Model & OOP</h2>

<p>
Object-Oriented Programming can mainly be used
during the implementation stage of the Waterfall Model.
</p>

<p>
OOP organizes software using classes and objects.
Concepts such as encapsulation, inheritance,
polymorphism and abstraction help developers
create structured and reusable software.
</p>

</div>

</section>


<!-- ADVANTAGES & DISADVANTAGES -->

<section class="pros-cons">

<h2>✅ Advantages & ❌ Disadvantages</h2>

<div class="pros">

<h3>✅ Advantages</h3>

<ul>

<li>Simple and easy to understand.</li>

<li>Each stage has clear goals.</li>

<li>Easy to manage and document.</li>

<li>Works well when requirements are fixed.</li>

</ul>

</div>


<div class="cons">

<h3>❌ Disadvantages</h3>

<ul>

<li>Difficult to make changes after a stage is completed.</li>

<li>Testing happens relatively late.</li>

<li>Not suitable when requirements change frequently.</li>

<li>Working software is available near the end.</li>

</ul>

</div>

</section>


<!-- REAL WORLD EXAMPLE -->

<section>

<div class="example">

<h2>💡 Real-World Example</h2>

<p>
Imagine developing a college examination management system.
</p>

<p>

First, the requirements are collected.

Then the system is designed.

Next, programmers implement the system.

After implementation, it is tested.

Then it is deployed for college staff and students.

Finally, it is maintained and updated when needed.

</p>

</div>

</section>


<!-- FOOTER -->

<footer>

<p>
College Project
</p>

<p>
Object-Oriented Software Programming
</p>

</footer>


<!-- JAVASCRIPT -->

<script>

function showInfo(stage) {

let message = "";

if (stage === "requirements") {

message =
"📋 Requirements: Identify and document what the users need from the software.";

}

else if (stage === "design") {

message =
"🎨 Design: Plan the software structure, architecture, database and user interface.";

}

else if (stage === "implementation") {

message =
"💻 Implementation: Programmers write the actual code based on the approved design.";

}

else if (stage === "testing") {

message =
"🧪 Testing: The software is tested to find and fix errors.";

}

else if (stage === "deployment") {

message =
"🚀 Deployment: The completed software is released and made available to users.";

}

else if (stage === "maintenance") {

message =
"🔧 Maintenance: The software is corrected, updated and improved after release.";

}

document.getElementById("info").innerHTML = message;

}

</script>

</body>
</html>
```

