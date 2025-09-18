<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sunnydale School</title>
  <style>
  
    h1 {
      font-size: 30px;
      font-weight: bold;
      color: #1E90FF;
    }

    
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }

    h2#mission {
      color: #32CD32; /* Mission Statement */
    }

    h2#upcoming-events {
      color: #FFA07A; /* Upcoming Events */
      background-color: #FFFFE0; 
      padding: 5px;
    }

    h2#contact {
      color: #20B2AA; /*Contact Info*/
    }

    .indoor{
background-color: #afeeee;

    }


    .outdoor {
      background-color: #AFEEEE;
      padding: 5px;
      border: 1px solid #B0E0E6;
    }

  
    .section {
      background-color: #f8f3f3;
      padding: 10px;
      margin-top: 10px;
    }

    
  
  </style>
</head>
<body>
  <!-- Step 1 -->
  <h1>Sunnydale School</h1>

  <!--(Mission Statement) Section-->
  <h2 id="mission">Mission Statement</h2>
  <p>
    At Sunnydale School, our mission is to help students discover a love for learning, encouraging their creativity, and guiding them to grow into responisble, caring members of the community.
  </p>

  <!-- (Upcoming Events) Section-->
  <h2 id="upcoming-events">Upcoming Events</h2>
  <ul>
    <li data-event-type="indoor" class="indoor">
      Science Fair - <span style="font-weight:bold; color:magenta;">June 10</span>
    </li>
    <li data-event-type="outdoor" class="outdoor" title="Event Type: Outdoor">
      Art Exhibition - <span style="font-weight:bold; color:blue;">June 15</span>
    </li>
    <li data-event-type="outdoor" class="outdoor" title="Event Type: Outdoor">
      Sports Day - <span style="font-weight:bold; color:orange;">June 20</span>
    </li>
  </ul>

<!--(Contact Info) Section-->
  <h2 id="contact">Contact Us</h2>
  <div class="section">
    <p>
      Email Address: 
      <a href="mailto:sdkidsschool@hub" title="Click to copy email">
        sdkidsschool@hub
      </a>
    </p>
    <p>
      Phone Number: 
      <a href="tel:+0908-3467-9076" title="Click to copy phone number">
        0908-3467-9076
      </a>
    </p>
  </div>
  <!--'Thanks for reaching out!' -->

</body>
</html>
