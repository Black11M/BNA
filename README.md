# input search nav
        *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}
.container{
    width: 100%;
    min-height: 100vh;
    padding: 5%;
    background-image: linear-gradient(rgba(0,8,51,0.9),rgba(0,8,51,0.9)),url('images/background.jpg');
    background-position: center;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: center;

}
.search-bar{
    width: 100%;
    max-width: 700px;
    background: rgba(255, 255, 255, 0.2);
    display: flex;
    align-items: center;
    border-radius: 60px;
    padding: 10px 20px;
    backdrop-filter: blur(4px) staurate(180%);
}
.search-bar input{
    background: transparent;
    flex: 1;
    border: 0;
    outline: none;
    padding: 24px 20px;
    font-size: 20px;
    color: #cac7ff;
}
::placeholder{
    color: #cac7ff;
}
.search-bar button img{
    width: 25px;
}
.search-bar button{
    border: 0;
    border-radius: 50%;
    width: 60px;
    height: 60px;
    background: #58629b;
    cursor: pointer;
}
.title{
    position:absolute;
    top: 10%;
    left: 27%;
    transform: translate(-50%,-50%);
    font-size: 150px;
    color: rgb(8, 234, 241);
    text-shadow: 1px 1px 1px #ac1b1b,
                1px 2px 1px #000000,
                1px 3px 1px #919191,
                1px 4px 1px #919191,
                1px 5px 1px #919191,
                1px 6px 1px #919191,
                1px 7px 1px #919191,
                1px 8px 1px #919191,
                1px 9px 1px #919191,
                1px 10px 1px #919191,
                1px 20px 40px rgba(0, 0, 0, 0.3);
}
h1 {
    background-color:rgba(0,8,51,0.9);
    text-decoration-line: overline;
}
        }
    </style>
</head>
<body>
    <h1 class="title">Black.M</h1>
    <div class="container">
        <form action="https://www.youtube.com/search" method="get" class="search-bar">
            <input type="text" placeholder="search anything" name="q">
            <button type="submit"><img src="images/search.png"></button>
        </form>
    </div>
</body>
</html>
