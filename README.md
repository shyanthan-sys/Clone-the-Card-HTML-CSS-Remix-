/*Clone-the-Card-HTML-CSS-Remix*/
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon.in: Samsung S25 Ultra 5G</title>
    <style>
        /* font imported through google fonts */
        @import url('https://fonts.googleapis.com/css2?family=Baloo+2:wght@400..800&family=Baloo+Bhai+2:wght@400..800&display=swap');

        body {
            background-color: black;
            margin: 0;
            font-family: "Baloo Bhai 2", sans-serif;
        }

        .main {
            display: flex;
            flex-wrap: wrap;
            align-items: flex-start;
            justify-content: center;
            margin: 20px;
            gap: 20px;

        }

        .phone {
            background-color: whitesmoke;
            width: 200px;
            height: 395px;
            border-top-left-radius: 4px;
            border-bottom-left-radius: 4px;
            text-align: center;
            padding: 20px 0;
            position: relative;
            left: 20px;
        }

        .phone img {
            max-width: 90%;
            height: auto;
            position: relative;
            top: 90px;
        }

        .content {
            background-color: rgb(254, 253, 253);
            padding: 15px;
            border-top-right-radius: 4px;
            border-bottom-right-radius: 4px;
            width: 100%;
            max-width: 600px;
            line-height: 1.3;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .star {
            font-size: 20px;
            color: rgb(228, 106, 7);
            margin-top: 10px;
        }

        .rating {
            font-size: medium;
            color: rgb(27, 132, 185);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            cursor: pointer;
        }

        .cost {
            margin-top: 10px;
            font-size: xx-large;
            font-weight: 450;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        /*styling for Discount text */
        .off {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin-top: 7px;
            color: red;
        }

        .people {
            color: gray;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin-top: 5px;
        }

        .delivery {
            margin-top: 15px;
        }

        .cart {
            background-color: rgb(255, 208, 0);
            border: 2px solid rgb(255, 208, 0);
            border-radius: 20px;
            padding: 8px;
            text-align: center;
            width: 97px;
            margin-top: 20px;
            cursor: pointer;
        }

        .cart:hover {
            background-color: rgb(255, 187, 0);
            width: 100px;
            height: 21px;
        }

        .othercolours {
            margin-top: 15px;
            color: rgb(0, 100, 109);
            text-decoration: underline;
            cursor: pointer;
        }

        .othercolours p:hover {
            color: rgb(0, 59, 65);
        }

         /* Media Queries for responsiveness */
        @media (max-width: 768px) {
            .content {
                width: 90%;
                font-size: 14px;
            }

            .cart {
                width: 100px;
            }
        }

        /* Mobile view adjustments */

        @media (max-width: 888px) {
            .main {
                flex-direction: column;
                align-items: center;
                margin: 10px;
            }

            .phone {
                width: 90%;
                position: relative;
                top: 20px;
                border-bottom-left-radius: 0px;
                border-bottom-right-radius: 0px;
                width: 400px;

            }

            .content {
                width: 95%;
                position: relative;
                left: 21px;
            }

            .star {
                font-size: 18px;
            }

            .cost {
                font-size: large;
            }

            .cart {
                width: 90px;
            }
        }
    </style>
</head>

<body>
    <div class="main">
        <!-- Phone image container -->
        <div class="phone">
            <img src="S25ultra.png" alt="Samsung Galaxy S25 Ultra">
        </div>
        <!-- Product content container -->
        <div class="content">
            <p>Samsung Galaxy S25 Ultra 5G Smartphone with Galaxy AI (Titanium Black, 12 GB RAM, 512 GB Storage),
                Titanium Frame, Snapdragon 8 Elite, 200MP Camera With Provisual...</p>
            <!-- Star rating -->
            <div class="star">
                ★★★★★ <span class="rating">241</span>
            </div>
            <!-- Purchase info -->
            <div class="people">
                100+ bought in the past month
            </div>
            <!-- Cost and discount -->
            <div class="cost">
                ₹1,29,999
            </div>
            <div class="off">
                (8% off)
            </div>
            <div class="people">
                Save extra with No Cost EMI
            </div>
            <!-- Delivery info -->
            <div class="delivery">
                FREE delivery <strong>Thu, 3 Jul</strong>
            </div>
            <div class="people">
                Service: Installation
            </div>
            <!-- Add to Cart button -->
            <div class="cart">
                Add to Cart
            </div>
            <!-- Other colors link -->
            <div class="othercolours">
                <p>+5 other colors/patterns</p>
            </div>
        </div>
    </div>
</body>

</html>
