# bibahhh
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pengingat Hari Ini</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f7f7f7;
            margin: 0;
            padding: 0;
        }
        #pesan {
            margin-top: 50px;
        }
        h1 {
            color: #ff69b4;
        }
        p {
            color: #333;
        }
        .reminder {
            font-size: 18px;
            color: #4CAF50;
            margin-bottom: 10px;
        }
    </style>
    <script>
        function showReminder(message) {
            alert(message);
        }

        function setReminder(reminder, time) {
            const now = new Date().getTime();
            const targetTime = new Date(now + time * 60 * 1000);
            const timeDiff = targetTime - now;

            setTimeout(function() {
                showReminder(reminder);
            }, timeDiff);
        }
    </script>
</head>
<body>
    <div id="pesan">
        <h1>Untuk Bibah</h1>
        <p class="reminder">Jangan lupa bahagia yah semoga lancar sidangnya!</p>
        <script>
            setReminder("Waktunya makan siang, jangan sampai lupa untuk mengisi perutmu!", 30);
        </script>

        <p class="reminder">aku sayang kamu</p>
        <script>
            setReminder("Sudah saatnya istirahat sejenak, tidurlah sebentar untuk segarkan pikiranmu.", 180);
        </script>

        <p class="reminder">Semangat calon SKOM</p>
        <button onclick="showReminder('Hai cinta, terima kasih telah hadir dalam hidupku. Setiap hari bersamamu adalah anugerah yang indah. Aku mencintaimu dengan segenap hatiku. Selamat hari yang istimewa, sayang. - Ranu')">Klik di sini!</button>
    </div>
    <img src="ANISA-HABIBAH_-A.P._-S.Kom..jpg" alt="" width="200" height="300">
</body>
</html>
