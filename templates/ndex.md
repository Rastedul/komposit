%%html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Калькулятор стоимости недвижимости</title>
</head>
<body>
    <h1>Калькулятор стоимости недвижимости</h1>
    <p>
        {% if message %}
        {{ message }}
        {% endif %}
    </p>
    <form action="" method="post">
        <p>
            <label>Площадь квартиры в м2:</label>
            <input type="text" name="area">
        </p>
        <p>
            <input type="submit">
        </p>
    </form>

</body>
</html>
