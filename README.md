# Ex.06 Restaurant Website
## Date: 29/12/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
~~~

<html>
<head>
    <title>TAMILNADU RESTAURANT</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
    <div class="nav">
        <a href="home.html" class="active">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>
    <div class="tit">
       <h5D> NALLA SAAPDUNGA</h5>
    </div>
    <div class="quote-box">
    <p>VAAZHGA VALAMUDAN</p>
    </div>
    
<footer class="f">
    <p>&copy; SARAVANAN K (25013282)</p>
</footer>

<html>
<head>
    <title>Tamil Restraunt</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="admin-container">
    <div class="nav">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html" class="active">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="admin-title">OUR MEMBERS</h1>

    <div class="admin-row">

        <div class="admin-card">
            <img src="Screenshot 2025-12-28 194643.png" align="center">
            <div class="admin-info">
                <h3>VIJAY</h3>
                <p class="role">CEO</p>
                <p>one of the humble leader</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="Screenshot 2025-12-28 194816.png" align="center">
            <div class="admin-info">
                <h3>AJITH KUMAR</h3>
                <p class="role"> Manager</p>
                <p>a well disciplined man</p>
            </div>
        </div>

        <div class="admin-card">
            <img src="Screenshot 2025-12-28 195217.png" align="center">
            <div class="admin-info">
                <h3>RAJINIKANTH</h3>
                <p class="role">Chef</p>
                <p>makes a dish more stylish</p>
            </div>
        </div>


        <div class="admin-card">
            <img src="Screenshot 2025-12-28 195747.png" align="center">
            <div class="admin-info">
                <h3>dhanush</h3>
                <p class="role">HR Manager</p>
                <p>Takes care of restraunt in a kindway</p>
            </div>
        </div>



    </div>
</div>
<footer class="f">
    <p>&copy; SARAVANAN K (25013282)</p>
</footer>
</body>
</html>

<html>
<head>
    <title> Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="menu-container">
    <div class="nav">
        <a href="rest.html">HOME</a>
        <a href="menu.html" class="active">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="menu-title">Our Menu</h1>

    <div class="cards">

        <div class="card">
            <img src="Screenshot 2025-12-28 200417.png" alt="Idly">
            <h3>Idly-30/-</h3>
            <p> Soft and sponge</p>
        </div>

        <div class="card">
            <img src="Screenshot 2025-12-28 200433.png"alt="appam">
            <h3>appam-40/-</h3>
            <p>pure quality.</p>
        </div>

        <div class="card">
            <img src="Screenshot 2025-12-28 200643.png" alt="chicken biriyani">
            <h3>chicken biriyani-220/-</h3>
            <p>spicy</p>
        </div>

        <div class="card">
            <img src="Screenshot 2025-12-28 200751.png" alt="chicken 65">
            <h3>chicken 65-150/-</h3>
            <p>crispy chicken .</p>
        </div>

        <div class="card">
            <img src="Screenshot 2025-12-28 200513.png" alt="Non veg meals">
            <h3>Non veg meals-180/-</h3>
            <p>traditional style .</p>
        </div>
    </div>
</div>
<footer class="f">
    <p>&copy; SARAVANAN K - (25013282)</p>
</footer>
</body>
</html>

<html>
<head>
    <title> Contact </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="contact-containerac">
    <div class="nav">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html" class="active">CONTACT</a>
    </div>
    <div class="contactquote">
        <p> suvachi paaru rusi nooru</p>
    </div>

    <div class="contact-card">
        
        <h1>Contact Us</h1>
        <p class="contact-quote">we'll always be here to fill your hunger</p>
      
        <div class="contact-details">
            <p><strong>Phone:</strong> 753457565378 </p> 
            <p><strong>Email:</strong> asaivam@gmail.com</p>
            <p><strong>Address:</strong> ASAIVA ULAGAM,Tiruvannamalai town,tamil nadu-606601</p>
        </div>
    </div>
</div>
<footer class="f">
    <p>&copy; SARAVANAN K (25013282)</p>
</footer>
</body>
</html>

body {
    margin: 0;
}
.container {
    width: 100%;
    height: 1580px;
    background-image: url("Screenshot 2025-12-28 205952.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    position: relative;
}
.nav {
    position: absolute;
    top: 40px;
    right: 60px;
}
.nav a {
    color: rgb(14, 1, 1);
    text-decoration: none;
    font-size: 18px;
    margin-left: 25px;
    font-weight: bold;
}
.nav a:hover {
    color: rgb(193, 5, 240);
}
.nav a.active{
    color: rgb(245, 9, 9);
    border-bottom: 2px solid rgb(11, 240, 95);
}
.tit {
    position: absolute;
    top: 16%;
    left:6%;
    font-family: 'merlin';
    font-size:80;
    font-weight: 300;
    color: #c4e90a;
    letter-spacing: 4px;
    text-transform: uppercase;
}
.quote-box {
    position: absolute;
    margin-top:200px;
    margin-left:100px;
    background: rgba(17, 179, 219, 0.792);
    border-radius: 0px;
    padding:10px;
    backdrop-filter: blur(8px);
    max-width:1000px;
}
.quote-box p {
    
    font-family: 'dauphin';
    font-size: 14px;
    color: #ffffff;
    letter-spacing: 1px;
    line-height: 1.6;
}
.offer-1{
    position: absolute;
    font-family: 'dauphin';
    font-size: 50px;
    color: #fdfdfd;
    margin-top:200px;
    margin-left:800px;
    background: rgba(44, 8, 252, 0.792);
    border-radius: 1px;
    padding:10px;
    backdrop-filter: blur(8px);
    max-width:100px;
 
}
.offer-box{
    position: fixed;
    bottom: 400px;               
    left: 1000px;
    width: 460px;
    background: rgba(230, 207, 3, 0.792);
    border-radius: 2px;
    padding:20px;
    box-shadow: 0 10px 28px rgba(27, 243, 3, 0.895);
    color: #fff;
    text-align: center;
    z-index: 60;
    backdrop-filter: blur(4px);
}
.offer-image{
    width: 300px;
    height: 110px;
    border-radius: 1px;
    object-fit: cover;
    border: 0px solid #ffffff;
    box-shadow: 0 4px 12px rgba(0,0,0,0.35);
    margin-bottom: 10px;
}
.offer-text h4{
    margin: 0 0 6px;
    font-family: 'Poppins', sans-serif;
    font-size: 18px;
    letter-spacing: 2px;
    text-transform: uppercase;
}
.offer-quote{
    margin: 0 0 8px;
    font-family: 'Great Vibes', cursive;
    font-size: 20px;
    color: #a20212;
}

.menu-container{
    background-image: url("Screenshot 2025-12-28 205952.png");
    padding-top:22px;
    height:1280px;
    width:100%;
}
.menu-title{
    text-align: center;
    margin-bottom: 30px;
    letter-spacing: 3px;
    color: rgb(43, 8, 37);
}
.menu-container .nav{
    height:1280px;
    color:#a20212;
    position: fixed;
    top: 20px;
    right: 60px;
}
.cards{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;

    gap: 20px;
    padding: 0 40px 40px;
}
.card{
    width: 220px;
    background: #d090ba;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
    padding: 15px;
    text-align: center;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    cursor: pointer;
}
.card:hover{
    transform: translateY(-8px) scale(1.03);
    box-shadow: 0 8px 20px rgba(0,0,0,0.25);
}
.card img{
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 6px;
    margin-bottom: 10px;
}
.card h3{
    margin: 8px 0;
}
.card p{
    font-size: 14px;
    color: #555;
}


.admin-container{
    height:1280px;
    background: url("Screenshot 2025-12-28 205952.png") center/cover no-repeat;
    padding: 80px 40px 40px;
    color: #9e1b47;
}
.admin-title{
    text-align: center;
    font-size: 40px;
    letter-spacing: 4px;
    margin-bottom:20px;
    text-transform: uppercase;
}
.admin-row{
    display: flex;
    flex-wrap: wrap;           
    justify-content: center;
    gap: 20px;
}
.admin-card{
    width: 260px;              
    display: flex;
    flex-direction: column;
    align-items: center;
    background: rgba(128, 16, 65, 0.522);
    color: #333;
    border-radius: 18px;
    padding: 18px 12px;
    backdrop-filter: blur(4px);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.admin-card:hover{
    transform: translateY(-6px);
    box-shadow: 0 10px 24px rgba(0,0,0,0.35);
}
.admin-card img{
    width: 130px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 10px;
}
.admin-info{
    text-align: center;
}
.admin-info h3{
    margin: 0 0 4px;
    font-size: 20px;
}
.admin-info .role{
    margin: 0 0 6px;
    font-weight: 600;
    font-size: 14px;
    color: #b0662d;
}
.admin-info p{
    margin: 0;
    font-size: 13px;
}


.contact-container{
    min-height: 100vh;
    background:url("Screenshot 2025-12-28 205952.png") no-repeat center/cover;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 100px;      
    padding-bottom: 80px;    
}
.contactquote{
    text-align: center;
    background-color:rgb(74, 39, 39) ;
    padding: 1px;
    border-radius:100px;
    margin-bottom: 20px;
}
.contactquote p{
    margin-top:50px;;
    font-family: 'monotype corsiva';
    font-size: 42px;
    color: #bfbfbf;
}
.contact-card{
    background: #ffffff;
    padding: 30px 40px;
    border-radius: 20px;
    margin-top:60px;
    text-align: center;
    max-width: 480px;
    width: 90%;
}
.contact-card h1{
    margin-bottom: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;
}
.contact-quote{
    font-style:normal;
    color: #7a5b3a;
    margin-bottom: 20px;
}
.contact-details p{
    margin: 6px 0;
    font-size: 15px;
}


.f{
    background: #111;
    color: #f5f5f5;
    text-align: center;
    padding: 10px 0;
    font-size: 13px;
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    z-index: 50;
}
.f p{
    margin: 0;
    letter-spacing: 1px;
}
~~~


## OUTPUT:
![alt text](<Screenshot 2025-12-28 233623.png>)
![alt text](<Screenshot 2025-12-28 233639.png>)
 ![alt text](<Screenshot 2025-12-28 233655.png>)
 ![alt text](<Screenshot 2025-12-28 233711.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
