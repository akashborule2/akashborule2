[8:48 pm, 16/01/2023] onkar shinde: <!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial=scale=1.0">
        <title>Responsive Portfolio using HTML and CSS</title>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css" 
        integrity="sha512-5A8nwdMOWrSz20fDsjczgUidUBR8liPYU+WymTZP1lmY9G6Oc7HlZv156XqnsgNUzTyMefFTcsFH/tnJE/+xBg==" 
        crossorigin="anonymous" referrerpolicy="no-referrer" />
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>
        <div class="container">
            <div class="left_Side">
                <div class="profileText">
                    <div class="imgBx">
                        <img src="img.jpeg">
          …
[8:48 pm, 16/01/2023] onkar shinde: @import url('https://fonts.googleapis.com/css?family=Poopins:200,300,400,500,600,700,800,900&display=swap');
*
{
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: 'Poopins', sans-serif;
}
body
{
background: lightblue;
display: flex;
justify-content: center;
align-items: center;
min-height: 100vh;
}
.container
{
 position: relative;
 width: 100%;
 max-width: 1000px;   
 min-height: 1000px;
 margin: 50px;
 background: white;
 display: grid;
 grid-template-columns: 1fr 2fr;
 box-shadow: 0 35px 55px rgb(0, 0, 0, 0.1);
}
.container .left_Side
{
    position: relative;
    background: #003147;
    padding: 40px;
}
.profileText
{
    position: relative;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-bottom: 20px;
    border-bottom: 1px solid rgba(255,255,255,0.2);
}
.profileText .imgBx
{
    position: relative;
    width: 200px;
    height: 200px;
    border-radius: 50%;
    overflow: hidden;
}
.profileText .imgBx img
{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.profileText h2
{
color: #fff;
font-size: 1.5em;
margin-top: 20px;
text-transform: uppercase;
text-align: center;
font-weight: 600;
line-height: 1.4em;
}
.contactInfo
{
    padding-top: 40px;
}
.title
{
    color: #fff;
    text-transform: uppercase;
    font-weight: 600;
    letter-spacing: 1px;
    margin-bottom: 20px;
}
.contactInfo ul
{
position: relative;

}
.contactInfo ul li
{
    position: rlelative;
    list-style: none;
    margin: 10px 0;
    cursor: pointer;
}
.contactInfo ul li .icon
{
display: inline-block;
width: 30px;
font-size: 18px;
color: aqua;
}
.contactInfo ul li span
{
    color: #fff;
   font-weight: 300; 
}
.contactInfo.education li
{
    margin-bottom: 15px;
}
.contactInfo.education h5
{
    color: aqua;
    font-weight: 500;
}
.contactInfo.education h4:nth-child(2)
{
    color: rgb(221, 211, 211);
    font-weight: 500;
}
.contactInfo.education h4
{
    color: #fff;
    font-weight: 300; 
}

.contactInfo.language .percent
{
    position: relative;
    width: 100%;
    height: 6px;
    background: #081921;
    display: block;
    margin-top: 5px;
}

.contactInfo.language .percent div
{
    position: relative;
    top: 0;
    left: 0;
    height: 100%;
    background: #03a9f4;
}

.container .right_Side
{
    position: relative;
    background: #fff;
    padding: 40px;
}
.about
{
    margin-bottom: 50px;
}
.about:last-child
{
    margin-bottom: 0;
}
.title2
{
    color: #003147;
    text-transform: uppercase;
    letter-spacing: 1px;
    margin-bottom: 10px;
}
p
{
color: #333;
}
.about .box
{
    display: flex;
    flex-direction: row;
    margin: 20px 0;
}
.about .box .topic
{
    min-width: 150px;
}
.about .box .topic h5
{
     text-transform: uppercase;
     color: #848c90;
     font-weight: 600;
}
.about .box .text h4
{
     text-transform: uppercase;
     color: #2a7da2;
     font-size: 16px;
}
.skills .box
{
    position: relative;
    width: 100%;
    display: grid;
    grid-template-columns: 150px 1fr;
    justify-content: center;
    align-items: center;
}
.skills .box h4
{
    text-transform: uppercase;
    color: #848c99;
    font-weight: 500;
}
.skills .box .percent
{
    position: relative;
    width: 100%;
    height: 10px;
    background: rgb(240, 235, 235);
}
.skills .box .percent div
{
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    background: #03a9f4;
}
.interest ul
{
    display: grid;
    grid-template-columns: repeat(4,1fr);
}
.interest ul li
{
    list-style: none;
    color: #333;
    font-weight: 500;
    margin: 10px 0;
}
.interest ul li .fa
{
    color: #03a9f4;
    font-size: 18px;
    width: 20px;

