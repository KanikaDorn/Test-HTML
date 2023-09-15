# Test-HTML
This test I create a website about tourism service that user can find the that they want to visits. In addition, they can see the detail, price and can contact for more information. 

<!DOCTYPE html>
<html lang="em">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=2.0">
    <title>Cambodia Travel Tours</title>
    <style>
        div.sticky {
            position: -webkit-sticky;
            position: sticky;
            top: 0;
            padding: 2px;
            background-color: #badbf0;
            border: 2px solid #cb0505;
        }
        body, h1, h2, p {
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f3f3f3;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        header h1 {
            font-size: 36px;
        }

        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 20px;
        }

        .tour-card {
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
            overflow: hidden;
        }
        div.fixed {
            position: fixed;
            bottom: 0;
            right: 0;
            width: 300px;
            background-color: #f6f1ef;
            border: 3px solid #73AD21;
        }
        .tour-card img {
            width: 100%;
            height: auto;
        }

        .tour-details {
            padding: 20px;
        }

        .tour-title {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .tour-description {
            font-size: 16px;
            margin-bottom: 20px;
        }

        .tour-price {
            font-size: 20px;
            color: #e74c3c;
        }

        .contact-button {
            display: block;
            background-color: #e74c3c;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            margin-top: 10px;
            text-decoration: none;
        }

        .contact-button:hover {
            background-color: #c0392b;
        }
    </style>
</head>
<body style="background-color: rgb(173, 250, 250);">
<div class="sticky"> Welcome to Cambodia Travel Tour</div>
    <header>
        <h1>Cambodia Travel Tours</h1>
        <p>Your gateway to exploring the beauty of Cambodia</p>
    </header>

    <div class="container">
        <div class="tour-card">
            <img src="cambodia-tour1.jpg" alt="Angkor Wat Tour">
            <div class="tour-details">
                <h2 class="tour-title">Angkor Wat Tour</h2>
                <p class="tour-description">Set along the Siem Reap River, this small provincial capital boasts hundreds of sightseeing opportunities such as well-<br>
                preserved colonial buildings, museums, traditional markets, and cultural performances. Following its rapid growth, the lively    <br>
                town offers all the facilities expected by experienced world travelers.  </p>
                <p class="tour-price">$499 per person</p>
                
                <a href="https://www.wendywutours.com.au/" class="contact-button">Contact Us</a>
            </div>
        </div>
        
        <div class="tour-card">
            <img src="cambodia-tour3.jpg" alt="Preah Sihanouk">
            <div class="tour-details">
                <h2 class="tour-title">Preah Sihanouk</h2>
                <p class="tour-description">Discover the vibrant capital city of Cambodia, Phnom Penh, and its cultural treasures.<br>
                Explore the ancient temples of Angkor Wat and experience the rich history of Cambodia.<br>
                Preah Sihanouk province, named after King Norodom Sihanouk since its independence from France in 1953, is known locally as Kampong Som.<br>
                Located 230 kilometers southwest of the Capital Phnom Penh, the province of Kampong Som has become one of the best seaside destinations in Asia</p>
                <p class="tour-price">$299 per person</p>
                <a href="https://www.wendywutours.com.au/" class="contact-button">Contact Us</a>
            </div>
        </div>
        <div class="tour-card">
            <img src="cambodia-tour2.jpg" alt="Phnom Penh Tour">
            <div class="tour-details">
                <h2 class="tour-title">Phnom Penh Tour</h2>
                <p class="tour-description">Discover the vibrant capital city of Cambodia, Phnom Penh, and its cultural treasures.<br>
                Phnom Penh is a veritable oasis compared to the modernity of other Asian capitals. A mixture of Asian exotica,<br>
                the famous Cambodian hospitality awaits the visitors to the capital of the Kingdom of Cambodia. Here in the capital,<br>
                are many interesting touristy sites.</p>
                <p class="tour-price">$399 per person</p>
                <a href="https://www.wendywutours.com.au/" class="contact-button">Contact Us</a>
            </div>
        </div>
    </div>

<div class="fixed">
Emergency Contact:<br>
097-779-3897(Dorn Kanika)
</div>
</body>
</html>
