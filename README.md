body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: rgb(189, 225, 122);
}

.header_text {
    font-family: 'Nunito';
    font-size: 50px;
    font-weight: bold;
    color: white;
    text-align: center;
    margin-top: 20px;
    margin-bottom: 0px;
}

.gif_container {
    display: flex;
    justify-content: center;
    align-items: center;
}


body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 90vh;
    background-color: rgb(189, 225, 122);
}

#noButton {
    position: absolute;
    margin-left: 150px;
    transition: 0.5s;
}

#yesButton {
    position: absolute;
    margin-right: 150px;
}

.header_text {
    font-family: 'Nunito';
    font-size: 40px;
    font-weight: bold;
    color: rgb(255, 255, 255);
    text-align: center;
    margin-top: 20px;
    margin-bottom: 0;
}

.buttons {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    margin-top: 20px;
    margin-left: 20px;
}

.btn {
    background-color: #ffffff;
    color: rgb(233, 48, 48);
    padding: 15px 32px;
    text-align: center;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    border: none;
    border-radius: 12px;
    transition: background-color 0.3s ease;
}

.gif_container {
    display: flex;
    justify-content: center;
    align-items: center;
}

@media only screen and (max-width: 320px) and (max-height: 568px) {
    body {
        height: 100vh;
    }

    .header_text {
        font-size: 20px;
    }

    img {
        height: 60vh;
    }

    .btn {
        padding: 10px 18px;
        font-size: 12px;
    }
}

@media only screen and (max-width: 414px) and (max-height: 736px) {
    body {
        height: 90vh;
    }

    .header_text {
        font-size: 28px;
    }

    img {
        height: 60vh;
    }

    .btn {
        padding: 15px 25px;
        font-size: 14px;
    }
}

<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="stylesheet" href="./yes_style.css">
        
    </head> 
    <body>
        <div class="container">
            <div >
                <h1 class = "header_text">Hurrayyyy!!</h1>
            </div>
            <div class="gif_container">
                <img src="https://media0.giphy.com/media/T86i6yDyOYz7J6dPhf/giphy.gif" alt="Cute animated illustration">
            </div>
        </div>
       
    </body> 
</html>

body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: rgb(189, 225, 122);
}

.header_text {
    font-family: 'Nunito';
    font-size: 50px;
    font-weight: bold;
    color: white;
    text-align: center;
    margin-top: 20px;
    margin-bottom: 0px;
}

.gif_container {
    display: flex;
    justify-content: center;
    align-items: center;
}

