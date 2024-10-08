- 👋 Hi, I’m @IkranButhul
- 👀 I’m interested in...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
IkranButhul/IkranButhul is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<!DOCTYPE html>
<html lang="en">

    <head>
        <meta charset="UTF-8">
        <title>CSS Cascade</title>
        <link rel="stylesheet" href="../CSS/style.css">
        </head>
        <body>
            <div id="outer-box" class="box">
                <div class="box">
                    <p>Yellow Text</p>
                    <div class="box inner-box">
                        <p class="white-text">White Text</p>               
                    </div>
                </div>
                <div class="box">
                    <p>Yellow Text</p>
                    <div class="box inner-box">
                        <p class="white-text">White Text</p>
                    </div>
                </div>
            </div>
        </body>

        .box {
    background-color: blue;
    padding: 10px;
}
.inner-box {
    background-color: red;
}

p {
    color: yellow;
    margin: 0;
    padding: 0;
}

.white-text {
    color: white;
}
#outer-box {
    background-color: purple;
   
}
