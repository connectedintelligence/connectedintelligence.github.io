---
layout: page
title: "2025 TICI Workshop - March 24 and 25"
sitemap: false
permalink: /workshop/
---
The first Texas A&M Connected Intelligence workshop took place on March 24th and March 25th. A few pictures from
the workshop and the schedule can be seen here.

<style>
.carousel-container {
    max-width: 800px;
    margin: 20px auto;
    position: relative;
}
.carousel-slide {
    display: none;
    text-align: center;
}
.carousel-slide img {
    max-width: 100%;
    height: auto;
}
.carousel-nav {
    text-align: center;
    margin-top: 10px;
}
.prev, .next {
    cursor: pointer;
    padding: 8px 16px;
    background-color: #500000;
    color: white;
    border: none;
    margin: 0 5px;
}
.prev:hover, .next:hover {
    background-color: #400000;
}
</style>

<div class="carousel-container">
    <div class="carousel-slide">
        <img src="/images/workshops/2025/pic1.JPG" alt="Workshop Photo 1">
    </div>
    <div class="carousel-slide">
        <img src="/images/workshops/2025/pic2.JPG" alt="Workshop Photo 2">
    </div>
    <div class="carousel-slide">
        <img src="/images/workshops/2025/pic3.JPG" alt="Workshop Photo 3">
    </div>
    <div class="carousel-slide">
        <img src="/images/workshops/2025/pic4.JPG" alt="Workshop Photo 4">
    </div>
    <div class="carousel-slide">
        <img src="/images/workshops/2025/pic5.JPG" alt="Workshop Photo 5">
    </div>
    <div class="carousel-slide">
        <img src="/images/workshops/2025/pic6.JPG" alt="Workshop Photo 6">
    </div>
    <div class="carousel-slide">
        <img src="/images/workshops/2025/pic7.JPG" alt="Workshop Photo 7">
    </div>
    <div class="carousel-slide">
        <img src="/images/workshops/2025/pic8.JPG" alt="Workshop Photo 8">
    </div>
    <div class="carousel-slide">
        <img src="/images/workshops/2025/pic9.JPG" alt="Workshop Photo 9">
    </div>
    <div class="carousel-slide">
        <img src="/images/workshops/2025/pic10.JPG" alt="Workshop Photo 10">
    </div>
    <div class="carousel-nav">
        <button class="prev" onclick="changeSlide(-1)">Previous</button>
        <button class="next" onclick="changeSlide(1)">Next</button>
    </div>
</div>

<script>
let slideIndex = 1;
showSlides(slideIndex);

function changeSlide(n) {
    showSlides(slideIndex += n);
}

function showSlides(n) {
    let slides = document.getElementsByClassName("carousel-slide");
    if (n > slides.length) {slideIndex = 1}
    if (n < 1) {slideIndex = slides.length}
    
    for (let i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
    }
    slides[slideIndex-1].style.display = "block";
}
</script>

{% comment %}
Welcome to The first Texas A&M Connected Intelligence workshop! The workshop will take place on March 24th
and March 25th on the Texas A&M University campus. 


<style>
details > summary {
    cursor: pointer;
    position: relative;
    padding-right: 25px;
}
details > summary:hover {
    color: #500000;
}
details > summary::after {
    content: "▼";
    position: absolute;
    right: 0;
    color: #500000;
    font-size: 0.8em;
    margin-top: 5px;
}
details[open] > summary::after {
    content: "▲";
}
</style>

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 20px 0;">
<div style="border: 1px solid #ddd; padding: 15px; background-color: #f9f9f9;">
<details>
<summary><h3 style="display: inline-block; margin: 0;">Venue </h3></summary>
<div style="margin-top: 15px;">
<strong>Room 297, Zachry Engineering Building</strong><br>
125 Spence Street<br>
College Station, TX 77843<br><br>

<strong> Location:</strong>
<a href="https://maps.app.goo.gl/8hu6GT9MXwGcvaR17"> View Zachry Building on Google Maps</a>

<strong> Note: </strong> Zachry Engineering Building is within walking distance from the Texas A&M Hotel 
and conference center.
</div>
</details>
</div>

<div style="border: 1px solid #ddd; padding: 15px; background-color: #f9f9f9;">
<details>
<summary><h3 style="display: inline-block; margin: 0;">Parking near venue </h3></summary>
<div style="margin-top: 15px;">
<strong>Polo Road Garage</strong><br>
<strong>Directions:</strong>
<ol>
<li>From University Drive, turn onto Polo Road</li>
<li>The garage entrance will be on your right</li>
</ol>
- 5-7 minute walk to Zachry Engineering Building<br>
- Pick up a parking ticket. We will validate parking for workshop attendees<br>
<a href="https://maps.app.goo.gl/RYx7uH1Jbms6Ng3P7">View Polo Garage on Maps</a>
</div>
</details>
</div>

<div style="border: 1px solid #ddd; padding: 15px; background-color: #f9f9f9;">
<details>
<summary><h3 style="display: inline-block; margin: 0;">Hotel Information </h3></summary>
<div style="margin-top: 15px;">
<strong>Texas A&M Hotel and Conference Center</strong><br>
177 Joe Routt Boulevard<br>
College Station, TX 77840<br><br>

To make reservations:
<ul>
<li>Call: (979) 260-2235</li>
<li>Book Online: <a href="https://www.texasamhotelcc.com">www.texasamhotelcc.com</a></li>
</ul>
</div>
</details>
</div>

<div style="border: 1px solid #ddd; padding: 15px; background-color: #f9f9f9;">
<details>
<summary><h3 style="display: inline-block; margin: 0;">Hotel Parking </h3></summary>
<div style="margin-top: 15px;">
<strong>Gene Stallings Blvd Garage</strong><br>
500 Gene Stallings Blvd <br> 
College Station, TX 77844 <br>
<strong>Directions:</strong>
<a href="https://maps.app.goo.gl/g9TPUhpEo3zkR54YA">View Gene Stallings Garage on Maps</a>
- Hotel is adjacent to the parking garage <br>
</div>
</details>
</div>
</div>
{% endcomment %}

### Workshop Schedule
{% raw %}
<table>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 20px;
            padding: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            font-size: 14px;
            text-align: left;
            table-layout: fixed;
        }
        th, td {
            padding: 12px;
            border: 1px solid #ddd;
            word-wrap: break-word;
            overflow-wrap: break-word;
        }
        th {
            background-color: #500000;
            color: white;
            position: sticky;
            top: 0;
            z-index: 1;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        tr:hover {
            background-color: #ddd;
        }
    </style>
</head>
<body>

    <table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Time</th>
      <th>Event/Speaker</th>
      <th>Details</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="font-size: 16px;"> <b> March 24, 2025 </b> </td>
      <td> </td>
      <td> </td>
    </tr>
    <tr>
      <td>8:00 – 8:30 AM</td>
      <td>Continental Breakfast</td>
      <td>Zachry Chevron Room 297</td>
    </tr>
    <tr>
      <td>8:30 – 8:40 AM</td>
      <td>Welcome and Introduction</td>
      <td>Costas Georghiades, Vice President for Research</td>
    </tr>
    <tr>
      <td>8:40 – 8:50 AM</td>
      <td> Remarks</td>
      <td>Arul Jayaraman, Executive Associate Dean</td>
    </tr>
    <tr>
      <td colspan="3"> <b> NextG Communication Systems </b> </td>
    </tr>
    <tr>
      <td>8:50 – 9:30 AM</td>
      <td> Srinivas Shakkottai</td>
      <td>TAMU</td>
    </tr>
    <tr>
      <td>9:45 – 10:15 AM</td>
      <td>Junyi Li</td>
      <td>Qualcomm</td>
    </tr>
   <!-- <tr>
      <td>10:15 – 10:30 AM</td>
      <td>Break</td>
      <td> </td>
    </tr>-->
    <tr>
      <td>10:30 – 11:00 AM</td>
      <td>Milap Majmundar</td>
      <td>AT&T Labs</td>
    </tr>
    <tr>
      <td>11:00 – 11:45 AM</td>
      <td>Panel: Open-RAN and 6G: Architecting the Next Wireless Revolution.  Moderator: Krishna Narayanan</td>
      <td>Panelists: Junyi Li, Milap Majmundar, Srinivas Shakkottai, Michael Fox, Sabit Ekin</td>
    </tr>
    <tr>
      <td>12:00 – 2:00 PM</td>
      <td>Lunch Served in Zachry 297 / Poster Presentations</td>
      <td>Virginia Brown Atrium</td>
    </tr>
    <tr>
      <td colspan="3"> <b> Autonomous Systems & Robotics </b> </td>
    </tr>
    <tr>
      <td>2:15 – 2:45 PM</td>
      <td>Craig Robinson</td>
      <td>Waymo</td>
    </tr>
    <tr>
      <td>3:00 – 3:30 PM</td>
      <td>Sri Saripalli</td>
      <td>TAMU</td>
    </tr>
    <tr>
      <td>3:45 – 4:15 PM</td>
      <td>Ajay Gummalla</td>
      <td>Bedrock Robotics </td>
    </tr>
    <tr>
      <td>4:15 – 5:00 PM</td>
      <td>Panel:End-to-End Learning: A New Beginning for Autonomous Robotics?  Moderator: Sri Saripalli</td>
      <td>Panelists: Ajay Gummalla, Craig Robinson, Swaminathan Gopalaswamy, Dylan Shell, Jason O'Kane</td>
    </tr>
    <tr>
      <td>6:00 PM-8:00PM</td>
      <td>Dinner for invitees and faculty</td>
      <td>Casa Mangiare</td>
    </tr> 
    <tr>
      <td style="font-size: 16px;"> <b> March 25, 2025 </b> </td>
      <td> </td>
      <td> </td>
    </tr>
    <tr>
      <td>8:00 – 8:30 AM</td>
      <td>Continental Breakfast</td>
      <td>Zachry Chevron Room 297</td>
    </tr>
    <tr>
      <td>8:30 – 8:45 AM</td>
      <td>Welcome and Introduction</td>
      <td>Narasimha Reddy, HOD, Dept. of ECE</td>
    </tr>
    <tr>
      <td colspan="3"> <b> AI/ML & Compute Systems </b> </td>
    </tr>
    <tr>
      <td>8:45 – 9:15 AM</td>
      <td>Joseph Boccuzzi</td>
      <td>NVIDIA</td>
    </tr>
    <tr>
      <td>9:30 – 10:00 AM</td>
      <td>Ishan Misra</td>
      <td>Meta</td>
    </tr>
    <tr>
      <td>10:15 – 10:45 AM</td>
      <td>Dileep Kalathil</td>
      <td>TAMU</td>
    </tr>
    <tr>
      <td>10:45 – 11:00 AM</td>
      <td>Break</td>
      <td> </td>
    </tr>
    <tr>
      <td>11:00 – 11:45 AM</td>
      <td>Panel: Beyond Generation: Is Reasoning the Next Leap in AI?  Moderator: Dileep Kalathil</td>
      <td>Panelists: Stefan Adalbjornsson, Joseph Boccuzzi, Shuiwang Ji, Tianbao Yang, Aftab Hussain</td>
    </tr>
    <tr>
      <td>11:45 – 12:30 PM</td>
      <td>Lunch Served in ZACH 297</td>
      <td> </td>
    </tr>
    <tr>
      <td>12:30:00</td>
      <td>Invited speakers head to RELLIS for tour</td>
      <td> </td>
    </tr>
  </tbody>
</table>

</body>
</html>
</table>
{% endraw %}
