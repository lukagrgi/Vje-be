<!DOCTYPE html>
<html lang="hr">
<body>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zadatak s odlomcima i div elementima</title>

    <style>
        body {
            display: flex;
            flex-wrap: wrap;           /* omogućava prelazak u novi red kad nema mjesta */
            justify-content: center;   /* centriraj elemente po širini */
            background-color: #f2f2f2;
            margin: 0;
            padding: 20px;
            font-family: Arial, sans-serif;
        }

        div {
            width: 45%;                /* otprilike pola širine s malim razmakom */
            border: 2px solid black;
            padding: 15px;
            margin: 10px;
            background-color: #f9f9f9;
            box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1);
            box-sizing: border-box;    /* uračunaj padding u širinu */
        }

        b {
            color: red;
        }

        /* 📱 Kad je ekran manji od 768px (tablet/mobitel) */
        @media (max-width: 768px) {
            div {
                width: 100%;           /* zauzmi cijelu širinu ekrana */
            }
        }
    </style>

    <div>
        <p>Južnokorejska kompanija  <b style="color:red">poznata</b> po pametnim telefonima i elektronici.</p>
        <p>Američka tehnološka  <b style="color:red">kompanija</b> poznata po iPhone, iPad i Mac uređajima.</p>
    </div>
    
    <div>
        <p>Kineska kompanija specijalizovana <b style="color:red">specijalizovana</b> za telekomunikacijsku opremu i telefone.</p>
        <p>Japanska kompanija koja proizvodi širok spektar elektronskih uređaja. <b style="color:red">elektronskih</b> uređaja.</p>
    </div>
            
   

    


</body>
</html>

