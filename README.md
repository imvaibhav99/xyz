# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <style>
     /******************************
Flexbox Layout
*******************************/

.header, .nav {
  display: -webkit-flex;
  display: flex;
  -webkit-flex-direction: column;
  flex-direction: column;
}

.header {
  justify-content: space-between;
}

.nav {
  -webkit-flex: 1;
  flex: 1;
  -webkit-justify-content: space-around;
  justify-content: space-around;
}

@media all and (min-width: 640px) {
  .header, .nav {
    -webkit-flex-direction: row;
    flex-direction: row;
  }
}

@media all and (min-width: 1030px) {
  .nav {
    -webkit-flex: none;
    flex: none;
  }
}



body {
  margin: 0;
  font-family: Helvetica;
  background: url('auctioneer hub.jpg') top center no-repeat;
  background-size: cover;
}

.header {
  padding: 1px 0;
  margin: 0 auto;
}

.logo {
  background: transparent url('auction logo.jpg') center center no-repeat;
  width: 70px;
  background-size: contain;
  text-indent: 100%;
  white-space: nowrap;
  overflow: hidden;
}

.nav {
  list-style: none;
}

.nav li {
  margin: 10px 0 80px 58px;
}

.nav li a {
  text-decoration: none;
  color: #fff;
  font-size: 15px;
  text-transform: uppercase;
}

.nav li a:hover {
  color: rgba(10, 255, 6, 0.992);
}

.nav li:last-child a {
  background: rgba(255, 1, 1, 0.877);
  border-radius: 2px;
  transition: 200ms ease-in-out;
  padding: 8px 16px 7px;
}

.nav li:last-child a:hover {
  background: rgba(254, 254, 7, 0.96);
  color: #0e0e0e;
}

@media all and (min-width: 1030px) {
  .header {
    width: 1030px;
    min-width: 768px;
  }
}   
    </style>
    <header class="header">
        <h1 class="logo">Logo</h1>
        <ul class="nav">
          <li><a href="C:\Users\Dell\Desktop\auction project\Explore.html">HOME</a></li>
          <li><a href="C:\Users\Dell\Desktop\auction project\contact .html">Contact</a></li>
          
          <li><a href="C:\Users\Dell\Desktop\auction project\sign up 2.html">Sign Up</a></li>
          <li><a href="sign in.html">Sign In</a></li>
        </ul>
      </header>
    
</body>
</html>
