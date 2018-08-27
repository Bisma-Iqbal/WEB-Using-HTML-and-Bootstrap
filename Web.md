# WEB-Using-HTML-and-Bootstrap
#######################Html Code with bootstrap#################
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Web engineer</title>

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- Latest compiled and minified JavaScript -->

    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>

    <link rel="stylesheet" type="text/css" href="default.css">
</head>
<body>
<div class="header">
    <div class="navbar navbar-style">
        <div class="container">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse"></button>
                <a href=""><img class="logo" src="image/logo.png"></a>
                <ul class="nav navbar-nav navbar-right">
                    <li><a href="">Home</a> </li>
                    <li><a href="">Projects</a> </li>
                    <li><a href="">News</a> </li>
                    <li><a href="">Gallery</a> </li>
                    <li><a href="">Contact US</a> </li>

                </ul>
            </div>
        </div>
    </div>
    <div class="container">
        <div class="row">
            <div class="col-sm-6">
                <h1 class="text"> Autumn Season </h1>
                <p>Autumn, also known as fall in American and Canadian English, is one of
                    the four temperate seasons. Autumn marks the transition from summer to
                    winter, in September or March</p>
                <a class="btn btn-first" href="#">Watch Videos</a>
                <a class="btn btn-second" href="#">Subscribe Us</a>

            </div>
            <div class="col-sm-6">
                <img src="image/download.jpg" class="img-responsive">


            </div>

        </div>
    </div>

</div>

</body>
</html>

************************** CSS Code ********************************

body{
    margin: 0;
    padding: 0;
}
.header{
    height: 100%;

}
.navbar-style{
    box-shadow: 0 5px 10px #efefef ;
    text-transform: uppercase;
}
.text{
    font-size: 50px;
    color: #ff8c00 ;
}
.logo{
    height: 80px;
    padding : 2px 10px;

}
li a{
    color: #000000;
}
a.btn
{
    margin: 30px 10px;
    width: 110px;
    padding: 10px;
    border-radius: 20px;
}
a.btn-first{
    background-color:#ff8c00;
    color: #fff;

}
a.btn-second{
    border: 1px solid #ff8c00;
    color: #333;
}
a.btn{
    background-color: #ffc800;
    color:#fff;
    box-shadow: 5px 5px 10px #999;


}
