- 👋 Hi, I’m @tobatssss
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!DOCTYPE html>
<html>
<head>
    <title>Array Methods</title>
    <style>
        
        /* Add unique styles */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .container {
            background-color: #fff;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
            text-align: center;
        }
        h1 {
            color: #333;
        }
        h2 {
            color: #666;
        }
        pre {
            background-color: #f9f9f9;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Array Methods</h1>
        <a href="https://github.com/tobatssss/tobatssss.git" target="_blank">this is my code</a>

        <h2>Original Array:</h2>
        <pre id="originalArray"></pre>

        <h2>Using .map():</h2>
        <pre id="mappedArray"></pre>

        <h2>Using .filter():</h2>
        <pre id="filteredArray"></pre>

        <h2>Using .reduce():</h2>
        <pre id="reducedValue"></pre>
    </div>

    <script>
        // Sample array
        const originalArray = [1, 2, 3, 4, 5];

        // Display the original array
        document.getElementById('originalArray').innerText = JSON.stringify(originalArray);

        // Using .map() to double each element
        const mappedArray = originalArray.map(item => item * 2);
        document.getElementById('mappedArray').innerText = JSON.stringify(mappedArray);

        // Using .filter() to filter even numbers
        const filteredArray = originalArray.filter(item => item % 2 === 0);
        document.getElementById('filteredArray').innerText = JSON.stringify(filteredArray);

        // Using .reduce() to calculate the sum
        const reducedValue = originalArray.reduce((accumulator, currentValue) => accumulator + currentValue, 0);
        document.getElementById('reducedValue').innerText = reducedValue;
    </script>
</body>
</html>

