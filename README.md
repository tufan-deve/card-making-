<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style4.css">
    <title>card</title>
</head>

<body>
    <div class="card">
        <div class="image">
            <img width="190px" height="95px"
                src="https://media.istockphoto.com/id/1208877516/photo/old-man-and-the-sea.jpg?s=1024x1024&w=is&k=20&c=wqCtwfowAeJvVDbuq28rDEVfx-c3Iy562yy-fs9IzZQ="
                alt="">
        </div>
        <div class="capsule">
            <span>Nature</span>
        
            <span>Lake</span>
        </div>

        <div class="content">
            <h1>Muna</h1>
            <p> He love the free fire game and want to be an esport player now </p>
        </div>

        <div class="button">
            <button> Read More</button>
        </div>
        

    </div>


</body>

</html>




body{
    background-color: grey;
    display: flex;
}
.card{
    background-color: whitesmoke;
    height: 320px;
    width: 200px;
    border-radius: 7px;
    padding:  4px;
    
}
.image{
    padding: 5px;
    
}
.image img{
    border-radius:7px;
}
.capsule{
    padding: 0 40px;
}
.capsule span{
    border: 1.5px solid black;
    padding: 0 6px;
    border-radius: 10px;
}
.content{
    padding: 5px;

}
.content p{
    color: rosybrown;
    text-align: center;

}
.content h1{
    color:royalblue;
    text-align:center;
}
.button{
    text-align: center;
    
}
.button button{
    padding: 3px;
    border-radius: 8px;
    background-color: rgba(239, 23, 23, 0.644);
    cursor: pointer;
}



