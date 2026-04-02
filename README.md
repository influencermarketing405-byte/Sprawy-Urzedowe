<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title></title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #002f6c;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    text-align: center;
}

.container {
    width: 100%;
    padding: 20px;
    box-sizing: border-box;
}

h1 {
    font-size: 8vw;
    font-weight: 900;
    margin-bottom: 25px;
    letter-spacing: 2px;
}

p {
    font-size: 4.5vw;
    margin: 10px 0;
    line-height: 1.4;
}

.iban {
    margin-top: 15px;
    font-size: 4.5vw;
    font-weight: bold;
    word-break: break-word;
}

.price {
    font-size: 5vw;
    margin: 12px 0;
}

.note {
    margin-top: 25px;
    font-size: 4vw;
    line-height: 1.5;
}

/* Optional: prevent breaking in key phrase */
.nowrap {
    white-space: nowrap;
}
</style>
</head>

<body>

<div class="container">
    <h1>SPRAWY URZĘDOWE</h1>

    <p>
        Wyślij na numer konta kwotę, w jakiej chcesz uzyskać poradę
    </p>

    <div class="iban">
        IBAN: DE67100110012901139404<br>
        BIC: NTSBDEB1XXX
    </div>

    <div class="price">15 min – 25€</div>
    <div class="price">30 min – 50€</div>
    <div class="price">60 min – 100€</div>

    <div class="note">
        Wykonaj przelew natychmiastowy, żeby otrzymać poradę od razu.<br><br>
        W treści przelewu koniecznie wpisz swój numer telefonu.<br><br>
        Otrzymasz od nas telefon od razu po otrzymaniu wpłaty.
    </div>
</div>

</body>
</html>
