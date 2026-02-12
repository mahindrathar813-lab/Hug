<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Hug Day 💖</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;500&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #ff9ecf, #ffc1e3, #ffd6ec);
    font-family: 'Poppins', sans-serif;
    overflow-x: hidden;
}

.container {
    text-align: center;
    padding: 30px 15px;
}

h1 {
    font-family: 'Great Vibes', cursive;
    font-size: 48px;
    color: #fff;
    text-shadow: 2px 2px 10px #ff69b4;
    animation: fadeIn 2s ease-in-out;
}

p {
    color: #fff;
    font-size: 18px;
    margin: 15px auto;
    max-width: 600px;
    line-height: 1.6;
}

.heart {
    font-size: 30px;
    animation: float 2s infinite ease-in-out alternate;
}

button {
    background: #ff69b4;
    border: none;
    padding: 12px 25px;
    border-radius: 30px;
    color: white;
    font-size: 16px;
    cursor: pointer;
    margin-top: 20px;
    box-shadow: 0 5px 15px rgba(255,105,180,0.4);
    transition: 0.3s;
}

button:hover {
    background: #ff1493;
    transform: scale(1.05);
}

.hidden-message {
    display: none;
    margin-top: 25px;
    background: rgba(255,255,255,0.2);
    padding: 20px;
    border-radius: 20px;
    backdrop-filter: blur(10px);
}

video {
    margin-top: 30px;
    width: 90%;
    max-width: 500px;
    border-radius: 20px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.2);
}

/* Animations */
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(-20px);}
    to { opacity: 1; transform: translateY(0);}
}

@keyframes float {
    from { transform: translateY(0px);}
    to { transform: translateY(-10px);}
}
</style>
</head>

<body>

<div class="container">

    <h1>Happy Hug Day My Babuuu 🥹🫂</h1>

    <p>
        Agar duniya thodi si door bhi ho jaye na…  
        toh bhi meri feelings kabhi kam nahi hoti 💗  
        Tum meri muskurahat ka reason ho,  
        meri shanti ho, meri pyaari si duniya ho ✨
    </p>

    <p>
        Kabhi kabhi bas ek hug hi kaafi hota hai  
        sab tension, sab udaasi mita dene ke liye 🤍  
        Aur aaj ka hug sirf tumhare liye hai 💕
    </p>

    <div class="heart">💖 💗 💞 💓</div>

    <button onclick="showMessage()">Click Here For Your Hug 🫂</button>

    <div class="hidden-message" id="hugMessage">
        <p>
            Pass nahi hu to kya hua…  
            dil mein toh hu real mein na sahi  
            virtually toh hug kar sakta hu apni choti si pyaari si betuuu koo 🥹🫂  
            I love you my bacha 💖  
            Yeh hug sirf apke liye hai…  
            Jab bhi udaas ho, isse yaad kar lena  
            main hamesha tumhare saath hu 🤍✨
        </p>

        <p>
            Tum meri sabse soft si feeling ho,  
            meri comfort place ho,  
            aur meri sabse pyaari si aadat ho 💗  
        </p>
    </div>

    <!-- Video Section -->
    <video autoplay loop muted>
        <source src="hug.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

</div>

<script>
function showMessage() {
    document.getElementById("hugMessage").style.display = "block";
}
</script>

</body>
</html>
