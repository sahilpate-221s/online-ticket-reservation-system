# online-ticket-reservation-system
Here I'm posting code for online ticket reservation  using HTML and CSS which helps you in your college projects .It provides an idea how to make any website ,also you can add Java script for complete fuctioning.



code for website :- HTML :


<html>

<head>
    <link rel="stylesheet" href="style.css">
    

    <title>
        Railway reservation system
    </title>

</head>

<body>
    <font size="45" color="white">
        <div class="heading">
            <h2>
                <center> Railway Reservation System </center>
            </h2>
        </div>

    </font>
    <div class="left-side">
        <form action="" process.html" method="post" onsubmit="getValues()">
            <div class="bookingslot">
                <h2 align="center" class="book-title1">BOOK TICKET</h2>
                <ul class="content">

                    <select required="" name="from" id="d" value="From" required>
                        <option value>From</option>
                        <option value="jaipur">Jaipur</option>
                        <option value="delhi">Delhi</option>
                        <option value="phagwara">Phagwara</option>
                        <option value="mumbai">Mumbai</option>
                        <option value="jalandhar">Jalandhar</option>
                        <option value="amritsar">Amritsar</option>
                        <option value="Ahemdabad">Ahemdabad</option>
                        <option value="surat">Surat</option>
                        <option value="jammu">Jammu</option>
                        <option value="chandigarh">Chandigarh</option>
                    </select>
                    <!-- br tag and <i></i> -->
                    <br>



                    <select required name="from" id="c">
                        <option value="">To</option>
                        <option value="jaipur">Jaipur</option>
                        <option value="delhi">Delhi</option>
                        <option value="phagwara">Phagwara</option>
                        <option value="mumbai">Mumbai</option>
                        <option value="jalandhar">Jalandhar</option>
                        <option value="amritsar">Amritsar</option>
                        <option value="Ahemdabad">Ahemdabad</option>
                        <option value="surat">Surat</option>
                        <option value="jammu">Jammu</option>
                        <option value="chandigarh">Chandigarh</option>
                    </select>
                    <br>
                    <input type="text" name="name" placeholder="Enter your name" required><br>

                    <input type="date" name="date" placeholder="dd-mm-yyyy" required><br>
                    <select name="select1" size="1" required>
                        <option value="All Classes">All Classes</option>
                        <option value="2s">Second Class</option>
                        <option value="1AC">First-AC class</option>
                        <option value="2AC">Second-AC Class</option>
                        <option value="3AC">Third-AC Class</option>
                    </select>
                    <br>



                    <button type="submit" value="Submit">Find Trains</button>


                </ul>
            </div>




        </form>

    </div>

    <div class="right-side">

        <ul class="menu-list">
            <li><a href="home.html" class>HOME</a></li>
           

            <li>
                <div class="dropdown">
                    <a  class="dropbtn">MEALS</a>
                    <div class="dropdown-content">
                        <a href="home.html">E-Catering</a>
                        <a href="home.html">Standard Menu Rates</a>
                        
                    </div>
                </div>
            </li>
<li>
                <div class="dropdown">
                    <a  class="dropbtn"> HOLIYDAY PACKAGES</a>
                    <div class="dropdown-content">
                        <a href="home.html">Special Trains</a>
                        <a href="home.html">Packages</a>
                        
                    </div>
                </div>
            </li>
            <li>
                
                <div class="dropdown">
                    <a href="#service-station" class="dropbtn"> SERVICE AT STATION</a>
                    <div class="dropdown-content">
                        <a href="home.html">Wi-Fi Railway Station</a>
                        <a href="home.html">Battery Cars</a>
                        <a href="home.html">E-Wheelchairs</a>
                        <a href="home.html">Retiring Rooms</a>
                    </div>
                </div>
                
            </li>
            <li><a href="home.html" class>CONTACT US</a>
            
            </li>
        </ul>
        <div class="image">
            <img height='350px' width='100%'
                src="train-image.jpg">
        </div>


        <div class="holidays-heading">
            <h2>HOLIDAYS</h2>

        </div>

        <div class="hl">
            <h2>Tourist Trains</h2>
            <P class="paragraph">
                IRCTC offers Exclusive Rail tour packages with confirmed train tickets, sight-seeing and meals for
                enchanting Nilgiri Mountains, Darjeeling, Kullu Manali, Kashmir, Gangtok or divine tours of Mata Vaishno
                Devi, Rameswaram, Madurai, Shirdi, Tirupati etc. Holiday packages/ Land packages to these destinations
                are also available.
            </P>
            <input type="text" name="name" placeholder="Search Trains" required><br>
        </div>


        <div class="hl">
            <h2>National Packages</h2>

            <P class="paragraph">
                Be it the spiritual devotee seeking blessings of Tirupati, Shirdi or Mata Vaishno Devi or the leisure
                traveller wanting to relish the Blue mountains of North East, Sand-dunes of Rajasthan, Hamlets of
                Ladakh, Wonders of Himalayas, Serene lakes or Picturesque Islands, IRCTC has it all. Discover India
                through IRCTC!

            </P>
            <input type="text" name="name" placeholder="Search National Package" required><br>

        </div>

        <div class="hl">
            <h2>International Packages </h2>
            <P class="paragraph">Best deals in International Holiday packages, handpicked by IRCTC, for Thailand, Dubai,
                Sri Lanka, Hong Kong, China, Macau, Bhutan, Nepal, U.K., Europe, USA, Australia etc. The packages are
                inclusive of sightseeing, meals, visa charges and overseas medical insurance to give you a hassle-free
                and memorable experience.

            </P>
            <input type="text" name="name" placeholder="Search International Package" required><br>
        </div>
    </div>

</body>

</html



code for css:: 


body {
    font-family: 'Open Sans', arial, sans-serif;
    background-image: url(background.jpg);
    background-repeat: no-repeat;
    
}



.bookingslot {
    padding: 20px 40px 20px 5px;
    text-align: left;
    display: block;
    background-color: rgba(250, 250,250, 0.3);
    margin-left: 0.1px;
}


.menu {
    width: 20%;
    padding: 10px;
}



.content ul {
    list-style-type: none;
    margin-left: 0.1px ;
    padding: 0;
}

.content li {
    /* padding: 10px; */
    margin-bottom: 10px;
    background-color: blue;
    color: aqua;
    text-decoration: bold;
    text-align: center;
}


.content input {
    margin: 8px 0;
    border: 1px solid #ccc;
    box-shadow: inset 0 1px 3px #ddd;
    border-radius: 4px;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    padding-left: 20px;
    padding-right: 20px;
    padding-top: 12px;
    padding-bottom: 12px;
    font-size: 15px;
    width: 262px;
}

.content select {
    margin: 8px 0;
    border: 1px solid #ccc;
    box-shadow: inset 0 1px 3px #ddd;
    border-radius: 4px;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    padding-left: 10px;
    padding-right: 20px;
    padding-top: 12px;
    padding-bottom: 12px;
    font-size: 15px;
    width: 262px
}

.content button {
    padding: 12px;
    background-color: #ffe165;
    border: none;
    color: #fff;
    /* border-radius: 4px; */
    font-weight: bold;
    margin-top: 15px;
    margin-left: 10px;
    width: 262px;
    font-size: 15px;
}

.book-title1 {
    margin-top: 5px;
    margin-left: 40px;
    color: #2f1dd3;
    display: block;
    font-size: 2.6rem;
    margin-bottom: 4px;
    text-transform: uppercase;
    font-weight: 400;
}


.left-side {
    float: left;

}

.right-side {
    float: right;
    margin-left: 0px;
    /* padding: 0px; */
}

.menu-list {
    margin-top: 0px;
    padding-right: 0px;
    background-color: rgba(250, 250, 250, 0.3);
}

.menu-list li {
    float: left;

    padding: 23px 30px 23px 26px;
    text-align: center;
    display: block;
    background-color: rgba(250, 250, 250, 0.3);
    margin-right: 1px;
    float: left;
    width: 140px;

}

.menu-list a {
    text-decoration: none;
    color: #0c0b05;
    font-stretch: ultra-condensed;
    font-family: fantasy;
}

.hl {
    padding: 10px 30px 30px 30px;
    text-align: center;
    display: block;
    background-color: rgba(90, 82, 82, 0.3);
    margin-right: 5px;
    float: right;
    width: 300px;
}

.holidays-heading {
    font-size: 24px;
    text-align: center;
    margin-top: 50px;
    margin-bottom: 25px;
    color: #080804;
    ;


}

.active {
    background-color: #030303;
}

.holiday-list-item h2 {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    color: rgb(0, 0, 0);

}

.rotate90 {
    -webkit-transform: rotate(90deg);
    transform: rotate(90deg);
}

.paragraph {
    overflow: hidden;
    line-height: 1.7;
    font-size: 0.9rem;
    text-align: justify;
    font-family: sans-serif;
    color: #121212;
}
.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f1f1f1;
    min-width: 160px;
     box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2); 
    z-index: 1;
}

.dropdown-content a {
    color: black;
    padding: 10px 0px;
    text-decoration: none;
    display: block;
}

 .dropdown-content a:hover {
    background-color: #ddd;
}

.dropdown:hover .dropdown-content {
    display: block;
}
