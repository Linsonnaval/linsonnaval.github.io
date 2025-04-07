<h3>Linsonjude "Linson" Naval</h3>
<h3>Program and Project Manager</h3>
  <div class="nav"><br>
    <a href="#Projects">▶ Jump to Projects section</a><br>
    <a href="#Awards and Publications">▶ Jump to Awards and Publications section</a><br>
    <a href="#Recommendations">▶ Jump to Recommendations section</a><br>
    <a href="#Miscellaneous Projects">▶ Jump to Miscellaneous Projects section</a><br><br>
  </div>

<hr>

<h3>Education</h3>
MBA - Northeastern University<br>
BA - University of Massachusetts at Amherst

<hr>

<h3>Resume</h3>
<a href="Linsonjude Naval Resume 2025.pdf">Link to resume - PDF<br>
<img src="Resume Screenshot.JPG" alt="Screenshot of resume" width="500"></a><br>

<hr>

<div class="Projects" id="Projects">
<h3>Projects</h3>

Note: Due to sensitive nature of many of my work projects (federal government - public trust), only some informal work projects shown at the moment.

<b>Northeastern AI Hackathon</b>
<a href="YOLO for Bird Flu Detection in Chickens.pptx">Link to Presentation<br>
<img src="Presentation.JPG" alt="Presentation" width="500"></a><br>
Our hackathon team was trying to leverage computer vision data to provide machine learning to a model in which cameras could identify chickens sick (avian flu or other aliments).  
<br><br>

</div>

<hr>

<br>

<b>Sample REST API</b>

<!--started weather coding here, got help from chatgpt but learned from it and updated on my own-->

<body> <div>

  <!-- Button to trigger weather fetch -->
  <center><button onclick="getWeather()">Fun with a REST API<br>What is the weather where Linson is?</button></center>

  <!-- Where the weather info will be displayed -->
  <div id="output"></div>

  <script>
    // Convert weather code to a human-readable description
    function getWeatherDescription(code) {
      const codes = {
        0: "Clear sky",
        1: "Mainly clear",
        2: "Partly cloudy",
        3: "Overcast",
        45: "Fog",
        48: "Depositing rime fog",
        51: "Light drizzle",
        53: "Moderate drizzle",
        55: "Dense drizzle",
        56: "Light freezing drizzle",
        57: "Dense freezing drizzle",
        61: "Slight rain",
        63: "Moderate rain",
        65: "Heavy rain",
        66: "Light freezing rain",
        67: "Heavy freezing rain",
        71: "Slight snowfall",
        73: "Moderate snowfall",
        75: "Heavy snowfall",
        77: "Snow grains",
        80: "Slight rain showers",
        81: "Moderate rain showers",
        82: "Violent rain showers",
        85: "Slight snow showers",
        86: "Heavy snow showers",
        95: "Thunderstorm",
        96: "Thunderstorm with slight hail",
        99: "Thunderstorm with heavy hail"
      };

      // Return the matching description or fallback
      return codes[code] || "Unknown weather condition";
    }

    // Main function to fetch and display weather
    async function getWeather() {
      try {
        // 1. Build the API request URL with Boston coordinates, Fahrenheit, and mph
        const url = 'https://api.open-meteo.com/v1/forecast?latitude=42.3601&longitude=-71.0589&current_weather=true&temperature_unit=fahrenheit&windspeed_unit=mph';

        // 2. Send request to Open-Meteo
        const response = await fetch(url);

        // 3. Parse the JSON response
        const data = await response.json();
        const weather = data.current_weather;

        // 4. Convert the weather code to text
        const description = getWeatherDescription(weather.weathercode);

        // 5. Display the weather info on the page
        document.getElementById('output').innerHTML = `
          <p><strong>Temperature:</strong> ${weather.temperature} °F</p>
          <p><strong>Wind Speed:</strong> ${weather.windspeed} mph</p>
          <p><strong>Conditions:</strong> ${description} (code ${weather.weathercode})</p>
          <p><strong>Time:</strong> ${weather.time}</p>
        `;
      } catch (error) {
        // Handle any errors (like network issues)
        console.error('Error:', error);
        document.getElementById('output').textContent = 'Could not fetch weather data.';
      }
    }
  </script>

<br>

<hr>
<!--ended weather coding here-->

<div class="Awards and Publications" id="Awards and Publications">
<h3><b>Awards and Publications</b></h3><br>
<i>Deloitte Collaboration Award<br>
<img src="Screenshot_20250312_152957.jpg" alt="Collaboration Award" width="500"><br><br>
Department of Energy Recovery Act<br>
<img src="DOE.jpg" alt="Recovery Act recognition" width="500"><br><br>
<a href="https://qualitysafety.bmj.com/content/25/12/993.1">BMJ Quality and Safety</i><br>
<img src="BMJ.JPG" alt="BMJ article screenshot" width="500"></a><br><br>
</div>

<hr>

<div class="Recommendations" id="Recommendations">
  
<h3><b>Recommendations</b></h3>
<b><i></i>Garrett Kephart - CEO and Co-Founder @ Earth Finance (Garrett managed Linson)</b>i></b><br>

I worked closely with Linson for 4 years during our time consulting to the U.S. Department of Energy (DOE). He is a proven delivery and sales leader with exceptional maturity and integrity. Linson is thoughtful, empathetic, and highly analytical. He makes extra effort to establish personal connections with his superiors, peers, and customers. You want something done right that exceeds expectations? Linson is the guy - I highly recommend him!!<br><br>

<b><i>Rachael Shapira - Product/Project Manager (reported to Linson)</i></b><br>

To Whom It May Concern: 

I am writing to support Linson Naval. It is a pleasure to recommend him because of his ability to balance the needs of the company and the needs of the employee, provide supportive guidance, and foster a positive and encouraging work environment. 

First, Linson demonstrates exceptional communication skills. As a team member at Ad Hoc LLC, I had the pleasure of working under Linson’s management. His ability to listen and make employees feel heard and supported made him an outstanding manager. It was truly a privilege to work with him. For example, when I had concerns about my workload, Linson took the time to sit down with me, listen carefully, and help me address the issues in a way that benefited both me and the company. This made me feel more confident and capable in my role. 

Linson also displays remarkable empathy and emotional intelligence in his leadership. For instance, he was able to give advice and correction without ever making me feel defensive or bad, which is particularly important since I can be pretty sensitive. His approach to constructive feedback made me feel motivated to improve rather than discouraged, fostering a culture of growth and trust. 

Finally, Linson is an exceptional mentor and cheerleader for his team. This trait has been of benefit to our company because his encouragement helped many employees, including myself, exceed our goals and develop professionally. 

Sincerely, 
Rachael Shapira<br><br>

<b><i>Steven Hovland - Staff Software Engineer at Ad Hoc (reported to Linson)</i></b><br><br>

Linson was excellent to work for. He was flexible and always focused on completing the work without burning out. He is always positive and willing to help figure out whatever is blocking the work or resolving a personal issue or things related to benefits. Linson is knowledgeable and quick to understand a technical problem or relate to a personal need.
</div>

<hr>

<div class="Miscellaneous Projects" id="Miscellaneous Projects">
<h3><b>Miscellaneous Projects</b></h3></div>

<i>Repairs</i><br>
<img src="Repair.jpg" alt="Car Repair" width="500"><br>
Replacing the power steering pump and rotted out lines to the pump. I got this car in 2008 and will do my best to keep it going for many more years. So far, replaced the steering pump, bumper, left tail light, side window seals and other little things.<br><br>

<i>Sewing</i><br>
Hobbes, Jake and Tubby Nugget stuffies (hand sewn)<br>
<img src="Stuffies.jpg" alt="Stuffies" width="500"><br>
I made these for my kids. I get better with each iteration. But, the kids love them nevertheless.<br><br>

<i>Softball</i><br>
<img src="Softball.jpg" alt="Softball" width="500"><br>
Playing softball with the UMass Alumni team on the National Mall next to the Washington Monument.<br><br>

<i>Wood work</i><br>
<img src="Woodwork.jpg" alt="Woodwork" width="500"><br>
Made a wooden memory box for my in-laws' anniversary. Felt liner and laser engraving.

<i>Jogging</i><br>
<img src="Newport.jpg" alt="running" width="500"><br><br>

<i>Photography</i><br>
<img src="landscape.jpg" alt="landscape" width="500"><br><br>

