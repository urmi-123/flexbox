# flexbox
flexbox using html css designed by illustrator 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style 1.css">
</head>
<body>
    <div class="container">
        <div class="iteam_container">
            <div class="text">meet our team</div>
        </div>
        <div class="row">
        <div class="profile-card">
            <div class="profile-content">
                <div class="profile-image">
                    <img src="card.jpg.jpg" alt="first user">
                </div>
            </div>
    </div>
    
</body>
</html>

body{
    margin: 0;
    padding: 0;
    background-color: rgb(19, 29, 36);
    font-family: sans-serif;
}
.team-container{
    width: 100%;
    height: auto;
}
.text{
    color: aqua;
    font-size: 25px;
    font-weight: 550;
    text-transform: uppercase;
    text-align: center;
}
.row{
    width: 60;
    margin: auto;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-items: center;
    justify-content: center;
}
