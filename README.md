<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Boden Harris">
    <title>The Honor System</title>
    <style>
        body {
            font-family: 'Times New Roman';
            margin: 0;
        }
        html {
            background-color: #FAFAFA;
        }
        h1 {
            color: #333; 
            text-align: center;
            position: sticky; 
            top: 0; 
            background-color: #f5ca56; 
            z-index: 10; 
            padding: 10px 0; 
            margin: 0;
            border-bottom: 6px solid #8c7124;
        }   
        #paragraph {
            background-color: blanchedalmond;
            border-radius: 5px; 
            border: 1px solid black; 
            padding: 10px;
            margin-top: 10px; 
        }   
       button {
            font-size: 16px;
            margin-top: 10px;
            padding: 5px 10px;
            font-weight: bold;
        } 
        iframe {
            display: block;
            margin: 50px 0 0 50%;
        }
        .image-container {
            display: flex; 
            justify-content: center; 
            gap: 20px; 
            margin-top: -1460px; 
            margin-left: 46%; 
        }
        img {
            display: block;
            width: 300px; 
            height: auto; 
            border-radius: 15px; 
        }
        .information {
            color: #333;
            min-height: 1000px; 
            background-color: #90aeac;
            width: 700px; 
            padding: 20px; 
            margin-top: 20px; 
            border: 1px solid black; 
            border-radius: 5px;
            font-size: 18px;
        }
        .information2 {
            color: #333;
            background-color: #90aeac;
            min-height: 180px; 
            padding: 20px; 
            margin-top: 5px; 
            margin-left: 0;
            border: 1px solid black; 
            border-radius: 5px; 
        }
        .information3{
            background-color: #934740;
            color: black;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px; 
            position: relative; 
            width: 100%; 
            border-top: 2px dotted #333; 
            max-height: 75px; 
            font-weight: bold;
            font-size: 14px;
        }
        #game {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            max-width: 700px;
            margin: 0 auto;
            margin-top: 40px;
            margin-left: 50%;
        }
        input[type="range"] {
            width: 100%;
            margin: 15px 0;
        }
        button {
            padding: 10px 20px;
            background-color: #8f642b;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #58421b;
        }
        #results {
            margin-top: 20px;
            background-color: #f9f9f9;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 4px;
            display: none; 
        }
        label {
            font-size: 14px;
            display: flex;
            align-items: center;
            justify-content: start;
            gap: 8px;
            margin-bottom: 10px;
        }
        input[type="checkbox"] {
            margin: 0;
        }
        .secondary-button {
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #2196F3;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 14px;
        }
        .secondary-button:hover {
            background-color: #1976D2;
        }table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
            background-color: #ffffff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f5ca56;
            color: #333;
            font-weight: bold;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        tr:hover {
            background-color: #f1f1f1;
        }

    </style>
</head>
<body>
    <h1>The Honor System</h1>

    <button onclick="toggleParagraph()">What is the honor sytem? ↓</button>
    <p id="paragraph">The honor system is a trust-based system where individuals are expected to act ethically without direct supervision or enforcement.</p>
    
    <div class="information">
        <h2>Why is the honor system important?</h2>
        <ul>
            <li>The honor system displays the trust, integrity, and responsibility of society. It encourages individuals to act ethically, without the risk of judgement or punishment.</li>
        </ul>
        <h2>Where do we see the honor system used?</h2>
        <ul>
            <li>The honor system is commonly found in scenarios like self-service payment stations, libraries, academic settings, and community-supported agriculture stands.</li>
        </ul>
        <h2>In which environments does it the work the best?</h2>
        <ul>
            <li>The honor system can take place in any environment, but succeeds the greatest in tight-knit communities, with positive values and a high social accountability. While it offers the potential to reduce costs for businesses and build greater customer loyalty, implementing the system proves challenging in most settings. Its effectiveness requires a mutual trust between individuals, which can be difficult to establish in highly competitive or valuable conditions, such as the academic realm. It is important to note that the success of the honor system depends on the values of the surrounding community, as our behavior is shaped by what our society considers normal.</li>
        </ul>
        <h2>Should your business use the honor system?</h2>
        <ul>
            <li>Using the honor system in a business depends on its nature and the customer base. It can be a cost-effective option for small operations or niche businesses that have a strong community. Below are some pros and cons to help determine whether the honor system is suitable for your specific situation:</li>
        </ul>
        <h2>Pros and Cons of the Honor System</h2>
    <table>
        <thead>
            <tr>
                <th>Pros</th>
                <th>Cons</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Reduces operational costs by minimizing staffing or security requirements.</td>
                <td>Vulnerability to theft and dishonest behavior by some customers.</td>
            </tr>
            <tr>
                <td>Builds trust and strengthens community relationships.</td>
                <td>May not work well in high-traffic or urban environments.</td>
            </tr>
            <tr>
                <td>Can enhance the reputation of the business as ethical and customer-friendly.</td>
                <td>Potential for inconsistent revenue due to non-payments.</td>
            </tr>
            <tr>
                <td>Encourages customer accountability and fosters a sense of responsibility.</td>
                <td>Requires a loyal and engaged customer base to be effective.</td>
            </tr>
        </tbody>
    </table>
    </div>

    <div class="information2">
        <h2>Want to explore more?</h2>
        <p>Follow any of the links! Or read my essay linked 
            <a href="https://docs.google.com/document/d/1Kw2pTP-p087RtMbjwZz-BT-duwx_rpSm8i9PztfvPMA/edit?tab=t.0" target="_blank">here</a>!
        </p>
        <ul>
            <li><a href="https://youtu.be/fhNPkr5bplE?si=yWQSpfkrYueqHNGQ" target="_blank">Why Tanner Farmstead may be shutting his market down</a></li>
            <li><a href="https://youtu.be/Et4sBb4hdaE?si=28R8irU8zlZtWT6N" target="_blank">This business does not use large security cameras</a></li>
            <li><a href="https://simplicable.com/culture/honor-system" target="_blank">Explore different places the Honor System is seen</a></li>
            <li><a href="https://medium.com/engage/the-honor-system-does-it-work-52a77362a644" target="_blank">
                Blogger Michael Rhodes breaks down the Honor System in different scenarios </a></li>
        </ul>
    </div>
    
    <div class="information3">
        <p>Created by Boden Harris, for English Writing at Umass Amherst and based off <a href="https://docs.google.com/document/d/1Kw2pTP-p087RtMbjwZz-BT-duwx_rpSm8i9PztfvPMA/edit?tab=t.0" target="_blank">
            my essay on the honor system
        </a>.</p>
        <p>Sources:  
            <a href="https://1000awesomethings.com/2024/11/19/68-the-honor-system-2/" target="_blank">
                Honor System Image
            </a> , 
            <a href="https://jonpsy101.medium.com/plagiarism-in-the-modern-era-487f1d627619" target="_blank">
                Plagiarism Image
            </a> , 
            <a href="https://www.youtube.com/watch?v=95_nVc21Bmg" target="_blank">
                Business Video
            </a>
        </p>
    </div>

    <div class="image-container">
        <img src="http://1000awesomethings.com/wp-content/uploads/2012/01/the-honor-system.jpg" alt="Honor System Image 2">
        <img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*dLN46oGerOPHIaBdwwhWMw.jpeg" alt="Honor System Image 1">
    </div>

    <iframe
        width="700" 
        height="394" 
        src="https://www.youtube.com/embed/95_nVc21Bmg" 
        title="YouTube video player" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
    </iframe>

    <div id="game">
        <h2>Run Your Own Pie Stand!</h2>
        <p>Set the price for your pies and experiment to see how much money you can earn in a day. Pay attention to how the customers react to price changes and the addition of cameras.</p>
        <label for="price">Pie Price: $<span id="price-display">20</span></label>
        <input type="range" id="price" min="10" max="30" value="20" step="1" oninput="updatePriceDisplay()" />
        <label>
            <input type="checkbox" id="cameras" /> Add Cameras ($20 to run per day)
        </label>
        <button onclick="startGame()">Start Selling</button>
        <button class="secondary-button" onclick="toggleSummary()">Hide Summary</button>
        <div id="results"></div>
    </div>

    <script>
        let summaryVisible = false;

        function updatePriceDisplay() {
            const price = document.getElementById('price').value;
            document.getElementById('price-display').textContent = price;
        }

        function startGame() {
            const price = parseFloat(document.getElementById('price').value);
            const addCameras = document.getElementById('cameras').checked;

            let honest = 0, dishonest = 0, theft = 0, totalMoney = 0;
            let customers = Math.floor(Math.random() * 15) + 10; // Random number of customers

            if (addCameras) {
                customers = Math.floor(customers * 0.75); // 35% fewer customers
                theftReduction = 0.85; // Theft reduced by 85%
            } else {
                theftReduction = 1; // No reduction in theft
            }

            if(price > 24)
            {
                customers = Math.floor(customers * 0.75); // 35% fewer customers
            }
            
            if(price < 16)
            {
                customers = Math.floor(customers * 1.4); // 35% fewer customers
            }

            for (let i = 0; i < customers; i++) {
                const decision = Math.random();
                if (decision < 0.6) { // 60% honest
                    honest++;
                    totalMoney += price;
                } else if (decision < 1 - .15 * theftReduction) { // 25% dishonest
                    dishonest++;
                    totalMoney += price * 0.7; // Partial payment
                } else if (decision < 0.8 + 0.15 * theftReduction) { // Adjusted theft rate
                    theft++;
                    totalMoney -= price; 
                    dishonest++;
                }
                else{
                    honest++;
                    totalMoney += price;
                }
            }

            if (addCameras) {
                totalMoney -= 20; // Subtract cost of cameras
            }

            document.getElementById('results').innerHTML = `
                <p><strong>Total Customers:</strong> ${customers}</p>
                <p><strong>Honest Customers:</strong> ${honest}</p>
                <p><strong>Dishonest Customers:</strong> ${dishonest}</p>
                <p><strong>Thefts:</strong> ${theft}</p>
                <p><strong>Total Money Earned:</strong> $${totalMoney.toFixed(2)}</p>`;
            document.getElementById('results').style.display = 'block';
            summaryVisible = true;
        }

        function toggleSummary() {
            const resultsDiv = document.getElementById('results');
            if (summaryVisible) {
                resultsDiv.style.display = 'none';
                summaryVisible = false;
            } else {
                resultsDiv.style.display = 'block';
                summaryVisible = true;
            }
        }
    </script>

    <script>
        function toggleParagraph() {
            const paragraph = document.getElementById('paragraph');
            const button = document.querySelector('button');
            if (paragraph.style.display === 'none') {
                paragraph.style.display = 'block';
                button.textContent = 'What is the honor sytem? ↓';
            } else {
                paragraph.style.display = 'none';
                button.textContent = 'What is the honor sytem? ↑';
            }
        }
    </script>

</body>
</html>
