
<!DOCTYPE html>
<html>
    <head>
        <title>Noah Valves</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="./CSS/style.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" />
    </head>
    <body>
        <section class="header"> 
            <nav>
                <a href="index.html">
                    <img src="../images/NoahLogo.png" alt="Noah Valves">
                </a>
                <div class="nav-list" id="navlist">
                    <i class="fa fa-times" id="bar" onclick="hideMenu()"></i>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About</a></li>
                        <li><a href="#products">Products</a></li>
                        <li><a href="#contactus">Contacts</a></li>
                    </ul>
                </div>
                <i class="fa fa-bars"  onclick="showMenu()"></i>
            </nav>
            <div class="home" id="home">
                <h1>NOAH VALVES COMPANY</h1>
                <p>Specialized Valve Manufacturer, Importer, Trader & Dealer different types of industrial Valves & Fittings.</p>
            </div>
        </section>
        <section class="about" id="about">
            <div class="row">
                <div class="col1">
                    <img src="../images/Pin-icon.png">
                    <h2>Our Products</h2>
                    <p>Our products cover a wide range of varieties of Industrial Valves, Dairy Fittings, Butt Weld Fittings, Compressor Ferrule Fittings and Investment Casting Fittings. Widely used in the Industries of Food & Breweries, Sugar, Pharmaceuticals, Fertilizers, Chemicals, Petroleum, Textile, Water, Thermal Power Plant & Nuclear</p>
                </div>
                <div class="col2">
                    <img src="../images/Pin-icon.png">
                    <h2>Mission</h2>
                    <p>Mission is to utilize the highest quality, progressive technologies to produce world class insdustrial valves. Using proactive continuous improvement methods, we are here to exceed our customer's expectations in quality, delivery, and cost through continuous improvement and customer interaction.
                    </p>
                </div>
                <div class="col3">
                    <img src="../images/Pin-icon.png">
                    <h2>Delivery</h2>
                    <p>You can depend on our experienced staff for courteous, prompt, and reliable service. We export and deliver at time. You can rely on us. Send us an email for a quote or to get more information on how we can help with your needs. We will get back to you the next working day.</p>
                </div>
            </div>
        </section>
        <section class="products" id="products">
            <h2>PRODUCTS</h2>
            <div class="product-row">
                <div class="product-col1">
                    <img src="../images/image--267.png">
                    <img src="../images/image--066.png">
                    <img src="../images/image--268.png">                
                    <img src="../images/image--078.png">
                    <img src="../images/image--100.png">
                    <img src="../images/image--000.png">

                </div>
            </div>
        </section>
        <section class="contactus" id="contactus">
            <h2>GET IN TOUCH</h2>
            <div class="contactus-row">
                <div class="contact">
                    <h3>Contact Info</h3>
                    <h4>Branch Address:</h4>
                    <p>Plot No-A-42, Nityanand Nagar, Behind-Kanha Sweets, Queen's Road Vaishali Nagar
                        Jaipur, Rajasthan - 302021</p>
                    <h4>Factory Address:</h4>
                    <p>371/373, Room No. 9, Grd Flr., Nooribai Abdullah Comp., Parshuram Pupala Marg,
                        Near Arab Gali Opp. Municipal Industrial Estate, Grant Road (E), Mumbai-400008</p>
                    <h4>Owner:</h4>
                    <p>Salim Khan</p>
                    <h4>Contact:</h4>
                    <p>+91 8234758253</p>
                    <h4>Email:</h4>
                    <p>info@noahvalvescomapny.com</p>
                </div>

                <div class="form">
                    <h3>Contact form</h3>
                    <form>
                        <input type="text" name="name" id="name" placeholder="Name">
                        <input type="email" name="email" id="email" placeholder="Email">
                        <input type="number" name="phone" id="phone" placeholder="Phone"> 
                        <textarea id="message" name="message" placeholder="Message" rows="5"></textarea>
                        <button type="submit" id="submit">SUBMIT</button>
                    </form>
                </div>
            </div>
        </section>


        <script>
            var navlist = document.getElementById("navlist");

            function showMenu(){
                navlist.style.right = "0";
                navlist.style.transition="1s";
            }

            function hideMenu(){
                navlist.style.right = "-220px";
                navlist.style.transition="1s";
            } 

        </script>


    </body>
</html>