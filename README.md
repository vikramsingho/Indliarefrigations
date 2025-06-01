# Indliarefrigations
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Indlia Refrigations</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: url('https://images.unsplash.com/photo-1615874959474-d609969a20ed?auto=format&fit=crop&w=1600&q=80') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        header, .container {
            animation: fadeIn 1s ease-in-out;
        }

        select:hover {
            transform: scale(1.05);
            transition: transform 0.3s ease;
        }

        header {
            background-color: rgba(255, 0, 0, 0.8);
            padding: 20px;
            text-align: center;
            border: 5px solid gold;
        }

        header h1 {
            color: gold;
            font-size: 2.5em;
        }

        .container {
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.6);
            margin: 20px;
            border-radius: 15px;
            border: 3px solid gold;
        }

        .section {
            margin-bottom: 20px;
        }

        select, button {
            padding: 10px;
            margin-top: 10px;
            font-size: 1em;
            border-radius: 10px;
            border: none;
        }

        .whatsapp-button {
            display: inline-block;
            background-color: #25D366;
            color: white;
            padding: 10px 20px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
            animation: pulse 2s infinite;
            transition: background-color 0.3s ease;
        }

        footer {
            background-color: rgba(255, 0, 0, 0.8);
            padding: 20px;
            text-align: center;
            font-size: 1.2em;
            border-top: 5px solid gold;
        }

        footer p {
            font-style: italic;
            font-weight: bold;
            margin: 10px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>INDLIA REFRIGATIONS</h1>
</header>

<div class="container">
    <div class="section">
        <h2>Select Option</h2>
        <select>
            <option value="repair">Repair</option>
            <option value="service">Service</option>
        </select>
    </div>

    <div class="section">
        <h2>Select Appliance</h2>
        <select>
            <option value="ac">AC</option>
            <option value="fridge">Fridge</option>
            <option value="water-cooler">Water Cooler</option>
            <option value="washing-machine">Washing Machine</option>
        </select>
    </div>

    <div class="section">
        <h2>Service Location</h2>
        <select>
            <option value="rajgarh">Rajgarh</option>
            <option value="jaipur">Jaipur</option>
        </select>
    </div>

    <a class="whatsapp-button" href="https://wa.me/919828417496" target="_blank">
        Contact on WhatsApp
    </a>
</div>

<footer>
    <p>SHOP ADDRESS ⚠️:- J D A COLONY SANGANER JAIPUR</p>
    <p>HOME ADDRESS ⚠️:- INDIRA COLONY NEAR RS MEMORIAL SCHOOL, RAJGARH SADULPUR</p>
    <p>WARNING ⚠️:- INSTANT PAYMENT NEEDED</p>
</footer>

</body>
</html>
