<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>finzeo</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;600;700&display=swap" rel="stylesheet">
<script src="https://use.fontawesome.com/56f1f1ee0d.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.3/css/fontawesome.min.css">
</head>
<body>
    <section class="header">
    <nav>
        <a href="index.html"><img src="images/logo.png"></a>
        <div class="nav-links" id="navlinks">
            <i class="fa fa-times" onclick="hidemenu()"></i>
            <ul>
                <li><a href="index.html">HOME</a></li>
                <li><a href="about.html">ABOUT</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
        </div>
        <i class="fa fa-bars" onclick="showmenu()"></i>
    </nav>
    <div class="text-box">
        <h1>An investment in knowledge pays the best interest</h1>
        <p>
            Get instant business loan home loan education loan etc 
            very low interest rates. apply for now. Leeds document required. 
            Quick loan process. Types: Home Loan, Business Loan, Loan, Online Loan.
        </p>
        <a href="" class="hero-btn">Visit us To know More</a>
    </div> 
    </section>

    <!----contact us----->
    <section class="cta">
        <h1>GET AN INSTANT QUOTE!</h1>
        <a href="" class="hero-btn">CONTACT US</a>
    </section>

    <section class="footer">
        <h4>About Us</h4>
        <p>
            A paragraph is a self-contained unit of discourse in writing dealing with a particular point or idea. <br>
            A paragraph consists of one or more sentences
        </p>
        <div class="icons">
            <i class="fa fa-facebook"></i>
            <i class="fa fa-twitter"></i>
            <i class="fa fa-instagram"></i>
            <i class="fa fa-linkedin"></i>
        </div>
        <p>Made by Vishnu Lakshmana Perumal</p>

    </section>
    
    
<!--------JS FOR TOGGLE MENU------------->
<script>
    var navlinks = document.getElementById("navlinks");

    function showmenu(){
        navlinks.style.right = "0";
    }
    function hidemenu(){
        navlinks.style.right = "-200px";
    }
</script>
</body>
</html>
