# QR_Generator

- [Demo Link](https://adishsharma.github.io/QR_Generator/)

- This is the Website made using HTML CSS JAVASCRIPT
- This website Creates QRCODE for a given input text easily.

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container{
    background-color: #E5E5E5;
    min-height: 100vh;
    border: solid 12px #1D1E4C;
}

.content{
    max-width: 900px;
    margin: 0 auto;
}

.img_box,img{
    width: 300px;
    height: 320px;
}

.img_box{
    filter: brightness(120%);
    filter: contrast(120%);
    filter: drop-shadow(10px 10px 10px silver);
    border: solid goldenrod;
    border-radius: 50%;
    overflow: hidden;
}

.top_section{
    display: flex;
    justify-content: space-between;
    margin-top: 100px;
    margin-bottom: 30px;
    align-items: flex-end;
}

.top_section h1{
    position: relative;
    left: 100px;
    margin-bottom: 5px;
    font-size: 50px;
    font-weight: 500;
    color:#1D1E4C;
    font-family: 'Noto Sans', sans-serif;
}

.top_section a{
    text-decoration: none;
}

.top_section h1:hover{
    margin-bottom: 5px;
    font-size: 50px;
    font-weight: 500;
    color: crimson;
    cursor: pointer;
    font-family: 'Noto Sans', sans-serif;
}

.top_section h4{
    position: relative;
    left: 100px;
    text-align: end;
    font-size: 25px;
    font-weight: bold;
    font-family: 'Nunito', sans-serif;
}

.about_box {
    display: inline-block;
}

@keyframes typing {
    from {width: 0}
    to {width: 76%}
}

@keyframes blinkTextCursor{
    from{border-right-color: #1D1E4C}
    to{border-right-color: transparent;}
}

.about_box h2{
    overflow: hidden;
    width: 0;
    border-right: 0.07em solid #1D1E4C;
    white-space: nowrap;
    font-size: 70px;
    font-family: 'Noto Sans', sans-serif;
    font-weight: 400;
    color: #1D1E4C;
    margin-bottom: 20px;
    animation: typing 4s normal steps(42,end) both, blinkTextCursor 500ms steps(44) infinite normal;
}

.about_box p{
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 1.2px;
    text-align: justify;
    font-family: 'Nunito', sans-serif;
}

.about_box{
    margin-top: 50px;
}

.legacy_box{
    margin-top: 50px;
    font-weight: bold;
    font-family: 'Nunito', sans-serif;
    font-size: 30px;
    color: #1D1E4C;
}

.achievements li{
    margin: 10px 0 0 50px;
    font-size: 15px;
    color: black;
    letter-spacing: 1.2px;
    font-weight: normal;
    text-align: justify;
}

footer{
    position: relative;
    left: 180px;
    margin: 50px 0 20px 0;
    text-align: end;
    font-size: 15px;
    font-family: "Nunito";
    font-weight: bold;
}

footer .link{
    color: crimson;
    text-decoration: none;
}


footer .name{
    color: crimson;
    text-decoration: none;
}

footer .my_name{
    position: relative;
    left: -180px;
    margin: 100px 0 20px 0;
    text-align: center;
    font-size: 18px;
    font-family: "Nunito";
    font-weight: bold;
}
