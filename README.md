<!DOCTYPE html>
<html lang="en">
  <style>
    
    body {
    margin: 0;
    padding: 0;
    font-family: Roboto , sans-serif;
    box-sizing: border-box;
}

header {
    width: 100%;
}

ul {
    list-style: none;
}

#nav_bar {
    float: right;

}

#nav_bar li {
    display: inline-block;
    padding: 8px;
}

#nav_bar #sign_in {
        background: #4887ef;
        margin-left: 10px;
        padding: 7px 15px;
        border-radius: 3px;
        font-family: bold;
}

.nav-links {
    color: #404040;
}

a {
    text-decoration: none;
    color: inherit;    
}

li.nav-links a:hover {
    text-decoration: underline;    
}

#Sign_In:hover {
    box-shadow: 1px 1px 5px #999;
}

#Sign_In {
    color: #fff;
    margin: 20px;
    padding: 15px;
}

.google #google_logo {
    text-align: center;
    display: block;
    margin: 0 auto;
    clear: both;
    padding-top: 112px;
    padding-bottom: 20px;
}

.form {
    text-align: center;
}

#form-search {
    width: 450px;
    border-radius: 10px;
    line-height: 32px;
    padding: 20px 10px;
}

.form #form-search {
    padding: 0 8px;
}

.button {
    text-align: center;
    padding-top: 30px;
    padding-right: 10px;
    margin-bottom: 300px;
}



.lang {
  padding-left: 40px;
}

footer {
    background: #f2f2f2;
    border-top: solid 2px #e4e4e4;
    bottom: 0;
    padding-bottom: 0;
    width: 100px;
}

footer ul, .footer-right li {
    display: inline;
    text-decoration: underline;
    color: #444444;
    font-size: 14px;
    margin: auto;
    padding: 13px;
}

footer ul, .footer-left li {
    display: inline;
    text-decoration: underline;
    color: #444444;
    font-size: 14px;
    margin: auto;
    padding: 13px;
}
  
footer ul a:hover {
    text-decoration: underline;
}
  
.footer-right {
    float: right;
}

.footer-left {
    float: left;
}

@media screen and (max-width: 100px) {
 
    li.nav-links a {
       display: none;
     }
     
    #google_logo {
      padding: 0;
    }
     
    .buttons {
      display: none;
    }
     
    #form-search {
      width: 80%;
   
    }
     
    footer {
      bottom: 0;
    }
     
    footer ul {
      float: none;
      padding-bottom: 2px;
       
    }
     
    .footer-left {
      float: left;
      text-align: center;
      margin: auto; 
      padding-top: 10px;
       
    }
     
    .footer-right {
      float: right;
      text-align: center;
      
    }
   }
   
   @media screen and (max-width: 565px) {
    
     li.nav-links a {
       display: none;
     }
     
     
    #google_logo {
      padding: 0;
    }
     
    .buttons {
      display: none;
    }
     
    #form-search {
      width: 80%;
   
    }
     
    footer {
   
      position:absolute;
      bottom:0;
      width:100%;
      height:60px;
    }
     
    footer ul {
      float: none;
      padding-bottom: 2px;
       
    }
     
    .footer-left {
      text-align: center;
      margin: auto; 
      padding-top: 10px;
       
    }
     
    .footer-right {
      float: right;
      text-align: center;
      
    }
   }

  </style>

<head>
    <title>Google</title>
    <link rel="stylesheet" type="text/css" href="google_page.css">

</head>
<body>

    <header>
    <nav>
        <ul id="nav_bar">
            <li class="nav-links" id="gmail"><a href="#">Gmail</a></li>
            <li class="nav-links"><a href="#">Images</a></li>
            <button id="Sign_in">Sign In</button>
        </ul>            
    </nav>
    </header>

    <div class="google">
        <a herf="#" id="google_logo"><img src="google_logo.png"></a>
    </div>

    <div class="form">
        <form>
        <label for="form-search">
            <input type="text" id="form-search" placeholder="Search or URL">
        </label>
        </form>
    </div>

    <div class="button">
        <input type="submit" value="Google_Search" id="google_search">
        <input type="submit" value="I'm Feeling Lucky" id="im_feeling_lucky">
    </div>

    <span class="lang">Morocco</span>

    <div class="footer">
    <ul class="footer-left">
        <li><a href="#">Advertising</a></li>
        <li><a href="#">Business</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">How Search works</a></li>
    </ul>

    <ul class="footer-right">
        <li><a href="#">Privacy</a></li>
        <li><a href="#">Terms</a></li>
        <li><a href="#">Setting</a></li>
        </ul>
    </div>
</body>
</html>
