nav ul li{
    display:inline-block;
    list-style:none;
    margin:10px 20px;
}

nav ul li a{
    color:#fff;
    text-decoration:none;
    font-size:18px;
    position:relative;
}
nav ul li a::after{
    content:'';
    width:0;
    height:3px;
    background:#ff004f;
    position:absolute;
    left:0;
    bottom:-6px;
    transition:0.5s;
}
nav ul li a:hover::after{
    width:100%;
}