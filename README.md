<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anonymous Confession for Jean</title>
    <style>
        body {
            background-color: lightpink;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            text-align: center;
        }
        .introduction {
            font-size: 11px;
            margin-bottom: 20px;
        }
        .envelope {
            width: 200px;
            height: 150px;
            background-color: #D8BFD8; /* Light purple */
            border: 2px solid #ccc;
            border-radius: 10px;
            display: inline-block;
            cursor: pointer;
            position: relative;
        }
        .envelope::before {
            content: "";
            position: absolute;
            top: 10px;
            left: 10px;
            right: 10px;
            bottom: 50px;
            background-color: #fff;
            border-radius: 5px;
        }
        .letter {
            display: none;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: #fff;
            border: 2px solid #ccc;
            padding: 20px;
            width: 80%;
            max-width: 600px;
            box-shadow: 0 0 10px rgba(0,0,0,0.5);
            z-index: 1000;
            text-align: justify;
            font-family: 'Times New Roman', serif;
            font-size: 9px;
            font-style: italic;
            font-weight: bold;
        }
        .reply-form {
            margin-top: 20px;
        }
        .reply-form textarea {
            width: 100%;
            height: 100px;
        }
        .close-btn {
            position: absolute;
            top: 10px;
            right: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Anonymous Confession for Jean</h1>
    
    <div class="introduction">
        Salamat sa Diyos dahil binigyan Niya ako ng pagkakataon na makilala ka. Ang buhay ko ay puno ng lungkot dahil sa pag-ibig na ito na hindi ko masabi sa harap mo. Ako ay parang alipin sa sarili kong damdamin, naghihintay sa isang salita na maaaring hindi dumating. Bakit ba kasi ganito ang nararamdaman ko, parang walang katapusan ang sakit na ito. Sana lang ay maintindihan mo ang lahat ng ito, kahit sa pamamagitan ng mga salita na ito.
    </div>
    
    <div class="envelope" onclick="showLetter()">
        <div style="position: absolute; bottom: 10px; left: 50%; transform: translateX(-50%); font-size: 12px; color: #333;">Tap to Open</div>
    </div>
    
    <div class="letter" id="letter">
        <span class="close-btn" onclick="hideLetter()">X</span>
        <p>Jean, sa loob ng maraming taon, ako ay nagiging tahimik na tagahanga mo 🐈‍⬛. Ang bawat ngiti mo ay nagbibigay liwanag sa araw ko na puno ng dilim. Hindi ko alam kung paano ko sasabihin ang lahat ng ito sa harap mo, kaya sa pamamagitan ng liham na ito, inilalabas ko ang damdamin ko.</p>
        <p>Ako ay nagiging alipin sa pag-ibig na ito, na nagiging dahilan ng mga luha ko sa gabi 💀. Ang pagmamahal ko sa iyo ay totoo, at hindi ito basta-basta. Sana ay mapansin mo ang mga maliit na bagay na ginagawa ko para sa iyo, kahit sa likod lamang.</p>
        <p>Jean, ang buhay ko ay nagiging masaya dahil sa iyo, kahit na hindi mo alam 🐈‍⬛. Ang pag-ibig na ito ay nagiging dahilan ng mga pangarap ko sa gabi. Sana ay maging masaya ka sa lahat ng ginagawa mo, dahil ikaw ang dahilan ng mga ngiti ko.</p>
        <p>Sana ay mapatawad mo ako kung nagiging bigat ang damdamin na ito 💀. Ang pag-ibig ko sa iyo ay hindi nagbabago, kahit na ano ang mangyari. Sana ay maintindihan mo ang lahat ng ito, kahit sa pamamagitan ng mga salita na ito.</p>
        <p>Sana ay maipahayag ko ito sa taong ipinangako ko, kung saan maaari akong mag-confess nang tama. Kahit na tumagal ito ng maraming taon, o kahit na tanggihan mo ako, ito ay aking pagpipilian na maghintay at humanga sa iyo sa katahimikan 🐈‍⬛.</p>
    </div>
    
    <div class="reply-form">
        <h2>Reply Anonymously</h2>
        <form action="https://galaxasiel.sayout.net" method="post" target="_blank">
            <textarea name="reply" placeholder="Write your reply here..."></textarea><br>
            <button type="submit">Send Reply</button>
        </form>
    </div>
    
    <script>
        function showLetter() {
            document.getElementById('letter').style.display = 'block';
        }
        function hideLetter() {
            document.getElementById('letter').style.display = 'none';
        }
    </script>
</body>
</html>
