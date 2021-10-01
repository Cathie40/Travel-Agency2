/*GENERAL*/

*{
    margin: 0px;
    padding: 0px;
} 

h1, h2, h3, h4{
    color : #444
}
h1{
    font-family: 'Crete Round', serif;
    font-size: 45px;
}   
   
h2{
    font-size: 55px;
}

h3{
    font-size: 30px;
}

h4{
    font-size: 24px;
}

p{
    line-height: 20px;
    color: #777;
}

    .orange{
        color: #ff7a00;
        font-size: 65px;
    } 
    .clear{
        clear: both;
    }
ul{
    list-style: none;
}
/*toutes les listes du site seront sans style*/

a {
    text-decoration: none;
    color: #444;
}

/*BODY*/

body{
    font-family: Arial, sans-serif;
    font-size: 15px;
}
.wrapper
{
    width: 940px;
    margin: 0 auto;
    padding: 0 10px;
}
  /*les marges seront de 0 en haut et bas & automatique à dte et gauche - le padding idem avec 10px dte et gauche*/

/*HEADER*/

   header{
        height: 120PX;
   }
   header h1{
       float: left;
       margin-top: 32px;
   }
   header nav{
       float : right;
       margin-top: 50px;
    }
   header nav ul li{
       display: inline-block;
       margin-right: 20px;
   }
   header nav ul li a{
       text-transform: uppercase;  /*uppercase : majuscule*/
       font-weight: bold;
    }
/*MAIN-IMAGE*/

#main-image{
    height: 580px;
    background: url(./Images/main.jpg);
 }
 #main-image h2{
     font-weight: normal;
     text-transform: uppercase;
     text-align: center;
     padding: 150px 0px 40px 0px;
     margin-bottom: 20px;
 }

 .button-1{
    display: block;
    width: 120px;
    height: 50px;
    background: #ff7a00;
    color: #fff;
    font-size: 20px;
    margin: 0 auto;
    line-height: 50px;
    text-align: center;
    border-radius:  3px;
}
.button-1:hover{
     background: #02b8dd;
}
    
/* STEPS*/

#steps ul{
    margin: 80px 0;
}
#steps ul li{
    width: 300px;
    float:left;
    padding-top: 140px;
    text-align: center;
    margin-right: 10px;
}
#steps h4{
    text-transform: uppercase;
    margin-bottom: 20px;
}
#steps p{
    margin-bottom: 20px;
}
#step-1{
    background: url('images/steps-icon-1.png') no-repeat top center;
}
#step-2{
    background: url('images/steps-icon-2.png') no-repeat top center;
}
#step-3{
    background: url('images/steps-icon-3.png') no-repeat top center;
}

/* POSSIBILITIES */


#possibilities
{
    background-color: #efefef;
    padding: 60px 0;
}
#possibilities article
{
    width: 460px;
    height: 270px;
    float: left;
    border-radius: 10px;
}
#possibilities article:first-child
{
    margin-right: 20px;
}
.overlay{
    background: rgba(255,255,255, 0.95);
    height: 100%;
    width: 190px;
    padding: 20px;
    border-radius: 10px 0 0 10px;
    text-align: center;
    box-sizing: border-box;
}
article h4{
    border-bottom:  1px solid #ddd;
    padding-bottom: 20px;
    text-transform: uppercase;
    margin-bottom: 20px;
    text-align: center;
}
#possibilities p{
    text-align: center;
    margin-bottom: 20px;
}
.button-2{
    color: #fff;
    background-color: #ff7a00;
    padding: 6px 20px;
    border-radius: 3px;
}
.button-2:hover{
    color: #fff;
    background-color: #02b8dd;
}

/*CONTACT*/

#contact
{
    padding: 60px 0;
    text-align: center
}
#contact h3
{
    width: 400px;
    text-transform: uppercase;
    margin: 0 auto 20px auto;
    border-bottom:  1px solid #02b8dd;
    padding-bottom: 20px;   
}
form
{
    margin: 60px 0 20px 0;
}
label
{
    font-weight: bold;
    font-size: 20px;
    margin-right: 10px;
    color: #777;
}
input[type="text"]
{
    padding:10px;
    font-size: 20px;
    margin-right: 20px;
    border: 2px solid #ddd;
    border-radius: 3px;
}
.button-3
{
    color: #fff;
    font-size: 20px;
    font-weight: bold;
    padding: 11px;
    background-color: #02b8dd;
    border-style: none;
    border-radius: 3px;
}
.button-3:hover
{
    color: #fff;
    background-color: #444;
}

/*FOOTER*/

footer{
    height: 260px;
    background-color: #444;
}
footer h1{
    color:#fff;
    text-align: center;
    padding-top: 80px;
}
.copyright
{
    text-align: center;
    font-weight: bold;
    padding-top: 30px;
    color: #777;
}
