<!DOCTYPE html>
<html>
<head>
    <title>Compound Interest Calculator</title>
    <style>
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        .input-group {
            display: flex;
            align-items: center;
            margin: 10px 0; /* Spacing */
        }
        .input-group label {
            margin-right: 10px; /* Spacing between label and input */
        }
        input[type="text"] {
            border-radius: 20px; /* Rounded corners */
            padding: 8px;
            border: 1px solid #ccc;
            width: 85px; /* Adjusted width for half the size */
            -webkit-appearance: none; /* Removes up/down arrows */
            text-align: center; /* Center text */
        }
        button {
            border-radius: 20px; /* Rounded corners */
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            background-color: #4CAF50; /* Green background */
            color: white; /* White text */
            font-size: 16px; /* Larger font size */
        }
        button:hover {
            background-color: #45a049; /* Darker green background on hover */
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Compound Interest Calculator</h2>
        <div class="input-group">
            <label for="principal">Principal ($):</label>
            <input type="text" id="principal" value="1,000">
        </div>
        <div class="input-group">
            <label for="rate">Annual Interest Rate (%):</label>
            <input type="text" id="rate" value="8">
        </div>
        <div class="input-group">
            <label for="years">Years:</label>
            <input type="text" id="years" value="5">
        </div>
        <div class="input-group">
            <label for="compound">Compounds per Year:</label>
            <input type="text" id="compound" value="1">
        </div>
        <button onclick="calculateInterest()">Calculate</button>
        <p id="result"></p>
    </div>

    <script>
        // Function to format number with commas for thousands and millions
        function numberWithCommas(x) {
            return x.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ",");
        }

        // Function to remove commas from number
        function removeCommas(x) {
            return x.replace(/,/g, "");
        }

        // Add event listener to principal input to format as user types
        document.getElementById("principal").addEventListener("input", function() {
            var value = removeCommas(this.value); // Remove existing commas
            this.value = numberWithCommas(value); // Format value with commas
        });
        
        function calculateInterest() {
            var principal = parseFloat(removeCommas(document.getElementById("principal").value));
            var rate = parseFloat(document.getElementById("rate").value) / 100;
            var years = parseFloat(document.getElementById("years").value);
            var compound = parseFloat(document.getElementById("compound").value);
            
            var amount = principal * Math.pow((1 + rate / compound), compound * years);
            var interest = amount - principal;

            // Format results with commas for thousands and millions
            var formattedAmount = numberWithCommas(amount.toFixed(2));
            var formattedInterest = numberWithCommas(interest.toFixed(2));

            document.getElementById("result").innerHTML = "Future Value: $" + formattedAmount + "<br>Interest Earned: $" + formattedInterest;
        }
    </script>
</body>
</html>
