
<img width="200" align="right" src="https://user-images.githubusercontent.com/77529535/104816402-097a5f80-5843-11eb-9d83-deadb3bb212c.gif?raw=true">

<h3 align="center">
  Welcome to Amr Eldesouky profile!
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28">
</h3>

<!-- Typing SVG by DenverCoder1 - https://github.com/DenverCoder1/readme-typing-svg --> 

<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg"><img src="https://readme-typing-svg.herokuapp.com/?lines=AI%20engineer;Always%20learning%20new%20things&font=Fira%20Code&center=true&width=440&height=45&color=f75c7e&vCenter=true&size=22"></a>
</p>



- 🏢 I'm a Software and AI Engineer.
- 👨‍💻 As a CS student, I'm constantly learning and exploring new technologies to improve my skills.
- 💬 Ask me about my experience with C, C++, python, Data Structure, Algorithms,Database, OOP, HTML, CSS, Javascript, .


### Connect with Me :



<a href="https://www.linkedin.com/in/amr-eldesouky-363163256" target="_blank" title="My LinkedIn Account"><img src="https://img.shields.io/badge/-Amr%20ElDesouky-0077B5?style=for-the-badge&logo=Linkedin&logoColor=white"/></a>
<a href="https://www.facebook.com/amro.aldesouky" target="_blank" title="My Facebook Account"><img src="https://img.shields.io/badge/-Amro%20AlDesouky-0077B5?style=for-the-badge&logo=Facebook&logoColor=white"/></a>
<a href="https://codeforces.com/profile/amraldsoqi" target="_blank" title="My Codeforces Account"><img src="https://img.shields.io/badge/-Amr%20AlDesouky-0077B5?style=for-the-badge&logo=Codeforces&logoColor=white"/></a>



### 🛠 &nbsp;Tech Stack
![C](https://img.shields.io/badge/-C-05122A?style=flat&logo=C)&nbsp;&nbsp;
![C++](https://img.shields.io/badge/-C++-05122A?style=flat&logo=C%2B%2B)&nbsp;
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-05122A?style=flat&logo=visual-studio-code&logoColor=007ACC)&nbsp;
![Visual Studio](https://img.shields.io/badge/-Visual%20Studio-05122A?style=flat&logo=visual-studio&logoColor=007ACC)&nbsp;
![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)&nbsp;
![SQL](https://img.shields.io/badge/-SQL-05122A?style=flat&logo=sqlite)&nbsp;
![GUI](https://img.shields.io/badge/-GUI-05122A?style=flat&logo=gui)&nbsp;
![MySQL](https://img.shields.io/badge/-MySQL-05122A?style=flat&logo=mysql)&nbsp;
![Pandas](https://img.shields.io/badge/-Pandas-05122A?style=flat&logo=pandas)&nbsp;
![NumPy](https://img.shields.io/badge/-NumPy-05122A?style=flat&logo=numpy)&nbsp;
![TensorFlow](https://img.shields.io/badge/-TensorFlow-05122A?style=flat&logo=tensorflow)&nbsp;
![Jupyter](https://img.shields.io/badge/-Jupyter-05122A?style=flat&logo=jupyter)&nbsp;
![MATLAB](https://img.shields.io/badge/-MATLAB-05122A?style=flat&logo=mathworks)&nbsp;



<script>
// Sample data (replace with your desired percentages)
var data = [
  { language: "C++", value: 35 },
  { language: "Python", value: 40 },
  { language: "HTML", value: 5 },
  { language: "CSS", value: 5 },
  { language: "JavaScript", value: 5 },
  { language: "SQL", value: 10 }
];

// Define the chart dimensions
var width = 400;
var height = 400;

// Create the SVG element
var svg = d3.select("svg")
  .attr("width", width)
  .attr("height", height);

// Define the radius
var radius = Math.min(width, height) / 2;

// Create the color scale
var color = d3.scaleOrdinal()
  .domain(data.map(d => d.language)) // Use language names for color mapping
  .range(d3.schemeSet3); // Choose a color scheme (adjust as needed)

// Define the pie chart layout
var pie = d3.pie()
  .value(function(d) { return d.value; }) // Set value accessor

// Create the pie chart slices
var pieData = pie(data);

// Create arc generator
var arc = d3.arc()
  .outerRadius(radius)
  .innerRadius(radius * 0.8) // Adjust inner radius for donut effect

// Draw pie chart slices
var g = svg.selectAll(".arc")
  .data(pieData)
  .enter()
  .append("g")
  .attr("class", "arc");

g.append("path")
  .attr("d", arc)
  .attr("fill", function(d) { return color(d.data.language); }) // Use color scale

// Add labels (optional)
g.append("text")
  .attr("text-anchor", "middle")
  .attr("transform", function(d) { return "translate(" + arc.centroid(d) + ")"; }) // Position labels
  .text(function(d) { return d.data.language + ": " + d.data.value + "%"; }); // Display language and percentage

</script>

