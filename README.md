# 5200411254
Rancangan Input, Proses, &amp; Output
html

<!DOCTYPE HTML>
<html>
    <head>
        <link rel="stylesheet" href="style.css">
    </head>
 
    
    <body>
        <div class="filter">
        </div>
        <h1>Send a message for the bride and the groom</h1>
        <div class="valentine_card">
            <form>
                <label>TO :</label><br><input type="text"><br>
                <label>Message :</label><br>
                <textarea></textarea><br>
                <button>SEND</button>
                
            </form>
        </div>
    
    </body>
</html>


css

@import url('shorturl.at/qrKYZ');
body{
    padding: 0;
    margin: 0;
    outline: 0;
    height: 100vh;
    background: url(shorturl.at/nqGV0);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
.filter{
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    background-color:
    opacity: .6;
    z-index: 1;
}
h1{
    position: absolute;
    width: 100%;
    z-index: 2;
    font-size: 4em;
    text-align: center;
    color: #fff;
    font-family: 'Courgette', cursive;
}
.valentine_card{
    position: absolute;
    z-index: 2;
    left: 50%;
    top: 50%;
    transform: translate(-50%,-50%);
    background: #fff;
    width: 40%;
    padding: 25px;
    font-family: 'Courgette', cursive;
}
.valentine_card label{
    font-size: 1.3rem;
}
.valentine_card input{
    width: 100%;
    font-size:1.3rem;
    font-family: 'Courgette', cursive;
    border: none;
    border-bottom: 1px solid black;
    margin: 10px 0;
}
*:focus{
    outline: none;
}
.valentine_card textarea{
    width: 100%;
    height: 150px;
    resize: none;
    font-size:1.3rem;
    font-family: 'Courgette', cursive;
    border: none;
    border-bottom: 1px solid black;
    margin: 10px 0;
}
.valentine_card button{
    border: none;
    background: transparent ;
    font-size: 1.5rem;
    float: right;
    font-family: 'Courgette', cursive;
    transition: .4s;
    
}
.valentine_card button:hover{
    color: #f44336;
}
