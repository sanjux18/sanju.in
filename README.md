@import url('https://fonts.googleapis.com/css2?family=Gupter:wght@400;500;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Gupter:wght@400;500;700&family=Lora:ital,wght@0,400..700;1,400..700&family=Source+Code+Pro:ital,wght@0,200..900;1,200..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Gupter:wght@400;500;700&display=swap');
*{
    margin: 0;
    padding: 0;
} 
html{
    font-size: 62.5%;
    scroll-behavior: smooth;
    
}
.sidebar{
    position: absolute;
    background-color: rgb(194, 189, 189);
    font-family: 'Fira Sans',Sans-Serif;
    height: 100vh;
    transition: transform 0.3s ease-in;
}
.sidebar nav{
     text-align: left;
}
.sidebar nav li{
    list-style: none;
    font-size: 24px;
    margin: 10px;
    /* border: 1px saddlebrown solid; */
    
}
.sidebar nav li a{
    text-decoration: none;
    color: black;
    
}
.Main{
    /* background-color: yellow; */
    width: 90vw;
}
.container{
    display: flex;
    overflow: hidden;
    
}
.infocontainer{
   /*  background-color: rgb(255, 0, 179); */
    height: 58vh;
    width: 80vw;
    margin: 144px auto;
    display: flex;
    justify-content: space-around;
}
.devInfo{
    font-size: 16px;
    display: flex;
    justify-content:  center;
    flex-direction: column;
    font-family: "Source Code Pro", monospace;
}
.hello{
    font-size: 3em;
    color: darkturquoise;
}
.name{
    font-size: 3em;
    font-weight: bold;
    font-family: 'Fira Sans',Sans-Serif;
    color: darkturquoise;

}
.about{
font-size: 2.5em;
color: darkturquoise;

}
.moreabout{
    font-size: 2em;
    margin-top: 23px;
    font-family: 'Fira Sans',Sans-Serif;
    color: darkturquoise;

}
.buttons {
margin-top: 2.2em;
font-size: 16px;
}
.btn{
padding: 9px 14px;
border-radius: 22px;
color: white;
background-color: dodgerblue;
font-weight: bond;
font-size: 2em;
margin: 3px 3px;
cursor: pointer;

}
.btn-sm{
font-size: 10px;
padding: 7px 13px;
margin: 10px 0;

}
.btn:hover{
background-color: white;
color: dodgerblue;

}
.devpic img{
    height: 58vh;
    
}
.contactform{
    padding: 0 34px;
    font-family: 'Fira Sans',Sans-Serif;
    margin: 88px;
    
}
.contactform h1{
    font-family: "Gupter", serif;
     /* padding: 12px 0; */
}
.contactform form div{
    padding: 10px 0;
    display: flex;
    flex-direction: column;
}
.contactform form div input{
    /* width: 26vw; */
    border-radius: 5px;
    margin: 6px 0 0 0;
    padding: 3px;
}
.contactform form{
    margin: 0 40px;
}
#emailHelp{
    /* padding: 34px; */
    font-size: 11px;
    color: midnightblue;
    margin: 0 5px;
    padding: 3px 0 0 0;

}
#form-check{
    flex-direction: row;

}
#form-check-input{
    width: 24px;
    margin: 3px 0;

}
.blogItem{
 margin: 20px;
 font-family: 'Fira Sans',Sans-Serif;
}
.blogContainer{
    margin:  60px;
}

h1{
    font-family: 'Fira Sans',Sans-Serif;
    margin: 23px;
}
p{
    font-family: "Source Code Pro", monospace;
}
.intro{
    margin:  60px;
}
.intro h2{
    margin: 12px;
    font-family: 'Fira Sans',Sans-Serif;
}
.intro p{
    margin: 12px;
    font-family: "Source Code Pro", monospace;
}
.skillcontainer{
    padding: 12px;
}
.skillItem{
    display: flex;
    align-items: center;
    font-family: "Source Code Pro", monospace;
    font-weight: 600;
}
.skill{
    width: 200px;
    height: 10px;
    background-color: red;
    border: 2px solid black;
}
.hundred{
    width: 200px;
    background-color: aqua;

}
.fifty{
    width: 125px;
    background-color: rgb(74, 159, 183);
}
.t5{
    width: 80px;
    background-color: yellow;
}
.t6{
    width: 100px;
}
.sidebarGo{
transform: translate(-443px,0px);
position: absolute;
}
.hamburger{
    position: absolute;
    cursor: pointer;
    top: 10px;
    left: 10px;
}
.ham{
    margin-top: 10px;
    margin-left: 10px;
}
.cross{
    margin-left: 185px;
    margin-top: 10px;
}
/* .hidden{
    height: 100%;
    
    backdrop-filter: blur(6px);
    background-color: red;
    position: absolute;
    /* z-index: -1; */
/* } */
@media (max-width: 1615px){
   
    .buttons{
        font-size: 6px;
    }
    .devinfo{
        font-size: 10px;
    }
     
  .contactform,.intro,.blogContainer{
            margin:50px 8px;
}

}
@media(max-width:768px)
    {
        html{
            font-size: 55%;
        }
        .devpic{
        display: none;
         } 
         .devInfo{
           /* display: flex;
           flex-direction: column;
           justify-content: center;
           align-items: center; */
           margin: 1rem 0 1rem 8rem;
           
           

         }
         /* 1fr==1rem */
         ul li a{
            font-size: 2.9rem;
            margin: 0rem;
            font-style: italic;

         }
         .sidebar nav li{         
           
           
            font-weight:500;
            color:#333;
            padding: 10px 0;
            width: 100%;
            border-width: 0;
            border-bottom: 0 solid rgb(10, 44, 42);
            transition: transform .9s;
          
            /* border: 2px solid rgba(0,0,0,.1); */
        }
        
        .sidebar nav li:hover{
            border-width: 3px;
        }
        .sidebar nav{
            padding: 50px;             
       }
       .cross{
        margin-left: 184px;
        margin-top: 10px;
        font-size: 3.9rem;
        border:2px solid #a3a2a2;
        padding: .0rem .4rem;
        border-radius: 2rem;
        height:19px;
        width: 19px;
        
        
    }
    .cross:hover{
        color:#fff;
        background-color: rgb(84, 82, 82);

    }
    }
@media(max-width:468px){
    html{
        font-size: 50%;
    }
.hello{
    font-size: 3rem;
    

}
.name{
    font-size: 4rem;
}
.about{
    font-size: 3.5rem;
}
.moreabout{
    font-size: 3.8rem;
    margin-top: .4rem;
}
.devInfo{
    margin: 0;
}
.buttons{
    margin-top: 2rem;
    /* margin-left: 2rem; */
    text-align: center;
    font-size: .8rem;
}
.sidebar ul li a{
    /* padding:0 20px; */
    font-size: 2.8rem;

}
.cross{
    font-size: 3.1rem;
}
} 




