# MULTIPLICATION-TABLE
<html>
<head>
    
</head>

<body>

    Number:
    <input type="text" id="num">
    <br><br>

    <button onclick="showTable()">Generate Table</button>

    <br><br>

    <div id="result"></div>

    <script>
        function showTable() {
            var number = document.getElementById("num").value;
            var table = "";

            for (var i = 1; i <= 10; i++) {
                table = table + number + " x " + i + " = " + (number * i) + "<br>";
            }

            document.getElementById("result").innerHTML = table;
        }
    </script>

</body>
</html>
