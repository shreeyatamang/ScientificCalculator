# ScientificCalculator
Design of Scientific Calculator Using html CSS and JS.
<!DOCTYPE html>
<html>

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Designing calculator using html,css and js</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <div class="calculator">
            <form>

                <div class="display">
                    <input type="text" name="display">
                </div>
                <div>
                    <input type="button" value="AC " onclick="display.value=' ' " class="operator ">
                    <input type="button" value="DE " onclick="display.value=display.value.tostring().slice(0,-1) " class="operator ">
                    <input type="button" value=". " onclick="display.value +='.' " class="operator ">
                    <input type="button" value="/ " onclick="display.value +='/' " class="operator ">

                </div>
                <div>
                    <input type="button" value="7 " onclick="display.value +='7' ">
                    <input type="button" value="8 " onclick="display.value +='8' ">
                    <input type="button" value="9 " onclick="display.value +='6' ">
                    <input type="button" value="* " onclick="display.value +='*' " class="operator ">

                </div>
                <div>
                    <input type="button" value="4 " onclick="display.value +='4' ">
                    <input type="button" value="5 " onclick="display.value +='5' ">
                    <input type="button" value="6 " onclick="display.value +='6' ">
                    <input type="button" value="- " onclick="display.value +='-' " class="operator ">

                </div>
                <div>
                    <input type="button" value="1 " onclick="display.value +='1' ">
                    <input type="button" value="2 " onclick="display.value +='2' ">
                    <input type="button" value="3 " onclick="display.value +='3' ">
                    <input type="button" value="+ " onclick="display.value +='+' " class="operator ">

                </div>
                <div>
                    <input type="button" value="00 " onclick="display.value +='00' ">
                    <input type="button" value="0 " onclick="display.value +='0' ">
                    <input type="button" value="=" onclick=" display.value=eval(display.value) " class=" equal " class="operator ">

                </div>





            </form>



        </div>
    </div>

</body>

</html>


