<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Travel Booking - Premium Edition</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <style>
    * {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #eaafc8, #654ea3);
      color: #222;
      overflow-x: hidden;
      min-height: 100vh;
    }

    body {
      display: flex;
      flex-direction: column;
    }

    main {
      flex: 1;
    }

    .topbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(0, 100, 100, 0.1);
      padding: 10px 20px;
      border-radius: 10px;
      margin: 20px;
    }

    .logo-area {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .logo-area img {
      height: 50px;
      width: 50px;
      border-radius: 50%;
      object-fit: cover;
      
    }

    .logo-text {
      color: #fff;
      font-size: 18px;
      line-height: 1.2;
      font-weight: bold;
    }

    .logo-text small {
      font-size: 12px;
      font-weight: normal;
    }

    .icon-area a {
      color: white;
      font-size: 22px;
      margin-left: 15px;
      transition: transform 0.3s ease;
    }

    .icon-area a:hover {
      transform: scale(1.2);
      color: #ffeb3b;
    }

    h1 {
      text-align: center;
      color: #fff;
      text-shadow: 2px 2px #ff4081;
    }

    form {
      max-width: 650px;
      margin: 30px auto;
      background: #ffffffb3;
      padding: 25px;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
    }

    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }

    input, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 2px solid #ccc;
      border-radius: 8px;
    }

    button {
      margin-top: 20px;
      padding: 12px;
      width: 48%;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: bold;
      font-size: 16px;
      background: linear-gradient(45deg, #ff0057, #7a00ff);
      color: white;
      box-shadow: 0 0 10px #ff4081, 0 0 20px #7a00ff;
      transition: all 0.4s ease;
    }

    button:hover {
      box-shadow: 0 0 20px #ff4081, 0 0 30px #7a00ff;
      transform: scale(1.05);
    }

    #bookNow {
      background: linear-gradient(45deg, #00f260, #0575e6);
      float: right;
    }

    #vehicleImages {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin-top: 40px;
    }

    .vehicle-img {
      width: 150px;
      height: auto;
      border: 2px solid #fff;
      border-radius: 15px;
      transition: transform 0.4s ease, box-shadow 0.4s ease;
      margin: 15px;
    }

    .vehicle-img:hover {
      transform: scale(1.1) rotate(45deg);
      box-shadow: 0 5px 20px #ff4081;
    }

    #fareResult {
      max-width: 650px;
      margin: 30px auto;
      background: #ffffffb3;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
      text-align: center;
      color: #333;
    }

    #fireworks {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: url('https://media.tenor.com/N1gAsrRpKz4AAAAi/hearts-fireworks.gif') center center no-repeat;
      background-size: cover;
      display: none;
      z-index: 9999;
    }

    footer {
      background: rgba(0, 0, 0, 0.3);
      color: white;
      padding: 20px;
      text-align: center;
      margin-top: auto;
      border-top: 1px solid #ccc;
    }

    footer ul {
      list-style: none;
      padding: 0;
    }

    footer ul li a {
      color: white;
      text-decoration: none;
    }

    footer div {
      margin-bottom: 10px;
    }
  </style>
</head>
<body>

  <main>
    <div class="topbar">
      <div class="logo-area">
        <img src="C:\Users\USER\Downloads\vv-removebg-preview.png" alt="Logo">
        <div class="logo-text">
          Sevensea International<br>
          <small>(Tours & Travels)</small>
        </div>
      </div>
      <div class="icon-area">
        <a href="https://wa.me/919345992444" target="_blank"><i class="fab fa-whatsapp"></i></a>
        <a href="https://www.instagram.com/sevensea.international" target="_blank"><i class="fab fa-instagram"></i></a>
        <a href="https://sevenseaholidays.com" target="_blank"><i class="fas fa-globe"></i></a>
      </div>
    </div>

    <h1>🌟 ROADWAYS TRIPS 🌟</h1>

    <form id="bookingForm">
      <label for="from">From:</label>
      <select id="from" required>
        <option value="">Select Departure</option>
        <option>Madurai</option>
        <option>Chennai</option>
        <option>Bangalore</option>
        <option>Kochi</option>
        <option>Trivandrum</option>
      </select>

      <label for="to">To:</label>
      <select id="to" required>
        <option value="">Select Destination</option>
        <option>Chennai</option>
        <option>Bangalore</option>
        <option>Coimbatore</option>
        <option>Kodaikanal</option>
        <option>Ooty</option>
        <option>Munnar</option>
        <option>Alleppey</option>
      </select>

      <label for="departure">Departure Date:</label>
      <input type="date" id="departure" required>

      <label for="return">Return Date:</label>
      <input type="date" id="return" required>

      <label for="vehicle">Vehicle Type:</label>
      <select id="vehicle" required>
        <option value="">Select Vehicle</option>
        <option value="sedan">Sedan (Dzire/Etios)</option>
        <option value="innova">Innova Crysta</option>
        <option value="tempo12">Tempo Traveller 12+1</option>
        <option value="tempo13">Tempo Traveller 13+1</option>
        <option value="tempo14">Tempo Traveller 14+1</option>
        <option value="tempo15">Tempo Traveller 15+1</option>
        <option value="minibus21">Mini Bus 21+1</option>
        <option value="minibus25">Mini Bus 25+1</option>
        <option value="bus50">Bus 50 Seater</option>
        <option value="bus56">Bus 56 Seater</option>
      </select>

      <label for="passengers">Number of Passengers:</label>
      <input type="number" id="passengers" min="1" required>

      <button type="submit">Calculate Fare</button>
      <button type="button" id="bookNow">Book Now</button>
    </form>

    <div id="vehicleImages">
      <img src="v1.jpg" alt="Sedan" class="vehicle-img">
      <img src="v2.jpg" alt="Tempo Traveller" class="vehicle-img">
      <img src="v3.jpg" alt="Mini Bus" class="vehicle-img">
      <img src="v4.jpg" alt="50 Seater Bus" class="vehicle-img">
    </div>

    <div id="fareResult"></div>
    <div id="fireworks"></div>
  </main>

  <footer>
    <div style="display: flex; flex-wrap: wrap; justify-content: space-around; text-align: left;">
      <div>
        <h3>Sevensea International</h3>
        <p>All rights reserved © 2025</p>
      </div>
      <div>
        <h4>Quick Links</h4>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="https://sevenseaholidays.com/packages/">Packages</a></li>
          <li><a href="https://sevenseaholidays.com/gallery/">gallery</a></li>
        </ul>
      </div>
      <div>
        <h4>Contact Us</h4>
        <p><i class="fas fa-map-marker-alt"></i> Madurai, Tamil Nadu</p>
        <p><i class="fas fa-phone"></i> +91 9345992444</p>
        <p><i class="fas fa-envelope"></i> sevenseatravels@gmail.com</p>
      </div>
    </div>
  </footer>

  <script>
    const vehicleRates = {
      sedan: { rate: 14, bata: 500 },
      innova: { rate: 18, bata: 600 },
      tempo12: { rate: 20, bata: 700 },
      tempo13: { rate: 21, bata: 700 },
      tempo14: { rate: 22, bata: 700 },
      tempo15: { rate: 23, bata: 800 },
      minibus21: { rate: 27, bata: 900 },
      minibus25: { rate: 29, bata: 900 },
      bus50: { rate: 45, bata: 500 },
      bus56: { rate: 58, bata: 500 }
    };

    document.getElementById('bookingForm').addEventListener('submit', function(e) {
      e.preventDefault();

      const from = document.getElementById('from').value;
      const to = document.getElementById('to').value;
      const departure = new Date(document.getElementById('departure').value);
      const returnDate = new Date(document.getElementById('return').value);
      const vehicle = document.getElementById('vehicle').value;

      const days = Math.ceil((returnDate - departure) / (1000 * 60 * 60 * 24)) + 1;
      const rateInfo = vehicleRates[vehicle];
      const approxKmsPerDay = 250;
      const totalKms = approxKmsPerDay * days;
      const baseFare = (rateInfo.rate * totalKms) + (rateInfo.bata * days) + 500;

      document.getElementById('fareResult').innerHTML = `
        <h2>Fare Estimate</h2>
        <p>From: <b>${from}</b> | To: <b>${to}</b></p>
        <p>Vehicle: <b>${vehicle.replace(/([A-Z])/g, ' $1')}</b></p>
        <p>Duration: <b>${days} Days</b></p>
        <p>Total Fare: <b>₹${baseFare}</b></p>
        <small>Includes: Driver Bata, Toll, Parking</small>
      `;
    });

    document.getElementById('bookNow').addEventListener('click', function() {
      const fireworks = document.getElementById('fireworks');
      fireworks.style.display = 'block';
      setTimeout(() => fireworks.style.display = 'none', 4000);
      alert("Booking confirmed! Our team will contact you soon.");
    });
  </script>

</body>
</html>
