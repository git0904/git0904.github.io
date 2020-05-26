<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>메인화면</title>
<link rel="stylesheet" href="./css/bg.css">
    <style>
        * { margin: 0; padding: 0; }
        #button {
            width: 160px;
            color:white;
            text-align: center;
            padding: 0px 0px 10px 0px;
            margin: 0px 0px 10px 0px;
            border: 1px solid #0400aa;
            background-color: #0400aa;
            font-size: 36px;
        }
        #button p { 
            font-size: 16px;
            text-align: left;
        }
        #button a:hover {
            text-decoration:none;
            text-align: center;
            color: white;
        }
        #content {
            text-align: center;
        }
        #title {
            font-family: "맑은 고딕", "돋움"; 
            text-align: center;
            padding: 20px;
            margin-bottom: 50px;
            color:brown;
            background-color: ;
            font-size: 5em;
        }
        #logo img{
            border-radius: 50%;
        }
        #profile p {
            font-size: 20px;
            margin: 10px;
        }
        #profile_introduce {
            font-size: 16px;
            margin-top: 50px;
            margin-bottom: 100px;
            padding-bottom: 100px;
        }
        #main_menu li a {
            display: inline;
            list-style-type: none;
            /* width: 155px; */
            border-bottom: 1px solid lightgray;
        }
        #profile_list li {
            list-style-type: none;
            padding: 5px;
        }
        #main_menu li {
            color : orange;
            list-style-type: none;
            display: inline;
            padding-left: 20px;
            font-size: 20px;

        }
        #main_menu li a:hover {
            color: orange;
            text-decoration: none;
            background-color: white;
        }
        #profile {
            border: 1px solid white;
        }
    </style>
</head>
<body>
<div id="wrapper">
        <div id="button">
            <a href="./index.html"></a>
            <p>인터넷기초실습 1YA</p>
        </div>
        <div>
            <ul id="main_menu">
                <li><a href="../hw2/index.html">HW02</a></li>
                <li><a href="../hw3/main.html">HW03</a></li>
                <li><a href="../hw4/main.html">HW04</a></li>
            </ul>
        </div>
        <div id="content">
            <h1 id="title">Internet Basic Practice</h1>
            <div id="logo">
                <img src="./img/dy.jfif" alt="logo" width="250">
            </div>
            <div id="profile">
                <p>컴퓨터소프트웨어공학과</p>
                <p>1학년 YA반 20202861 최우진</p>
            </div>
            <div id="profile_introduce">
               <ul id="profile_list">
                   <li>20학번으로 동양미래대학교에 입학하였습니다.</li>
                   <li>#맛있는 음식 #운동 #게임</li>
               </ul>
            </div>
        </div>
</div>
</body>
</html>
