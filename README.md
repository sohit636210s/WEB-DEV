
This is E commerce website Which i have creat and I created This Websit for improve My skills
In This Website use  Only HTML CSS
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Best Online Food Delivery Service in India| OnllineFubu.com</title>
    <style>
        * {
           margin: 0;
            padding: 0;
        }

        /* css Variables */
        :root {
            --navbar--height: 59px;
        }

        /* For logo CSS */

        /* For navbar Bar CSS */
        #navbar {
            position: absolute;
            
        }

        #navbar {
            display: flex;
            /* background-color: rgb(88, 216, 216); */
            height: 60px;
            align-items: center;
            font-family: bree serif', serif;
        }

        #navbar::before {
            content: "";
            background-color: black;
            position: absolute;
            height: 100%;
            width: 100%;
            z-index: -1;
            opacity: 0.1 ;

        }

        /*  Navigation bar: logo and image css */
        .log {
            margin: 43px;
            margin-top: 48px;
        }

        .log img {

            width: 50px;
            height: 48px;
            border-radius: 50%;
        }

        /* Navigation Bar: and LIst style */
        /* color white */
        ul {
            display: flex;
        }

        #navbar ul li {
            list-style: none;
            


        }

        #navbar ul li a {
            color: white;
            display: block;
            padding: 3px 22px;
            border-radius: 20px;
            text-decoration: none;

        }

        #navbar ul li a:hover {
            color: black;
            background-color: white;
            
        }

        /* Home Section CSS aDD */
        #home{
            display: flex;
            flex-direction: column;
            height: 700px;
            padding: 3px 200px;
            justify-content: center;
            align-items: center;
        }
        #home::before{
            content: "";
            position: absolute;
        
        background: url('S:/Image for Project/Background1.avif') no-repeat center center;
        background-size: cover;
        height: 100%;
            width: 100%;
            z-index: -1;
            opacity: 0.89;
            
        }
        #home h1{
            display: flex;
            color: white;
            text-align: center;
            font-family: bree serif',serif;

        }
/* sarvices section */


#services{
    
    display: flex;
    
    
}
#services .box{
    
    height: 250px;
    border: 5px solid rgb(20, 19, 19);
    border-radius: 22px;
    margin: 34px 50px ;
    padding: 20px;
    
    
}
#services img{
    height: 160px;
    border-radius: 40px;
  margin-left: 26%;
}


        /* Utility Class */
        .h-primary{
            font-size: 2.8rem;
            padding: 12px;
            font-size: 3.8rem;
            margin-top: 30px;
            text-align: center;
             font-family: bree serif',serif;
            
        }
        .h-primary p{
           font-family: bree serif',serif;
            }

            .h-secondery{
                
                text-align: center;
                justify-content: center;
            }


       

        #home p{
            color: white;
            text-align: center;
            font-size: 1.1rem;
            font-family: 'bree serif', serif;
        }
        .btn{
            padding: 6px 20px;
            border: 2px solid white;
            background-color: rgb(16, 1, 1);
            color: white;
            margin-top: 20px;
            font-size: 1.rem;
            border-radius: 32px;
            cursor: pointer;
        }
        .btn:hover{
            color: black;
            background-color: white;
        }
       /* Client Section For CSS ADD */
        #client-section{
            height: 344px;

        }
        .client{
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .client-item{
            display: flex;
            margin: 2px;
            display: flex;
            justify-content: center;
            height: 140px;
        }
        client-item::before{
           content: "";
           position: absolute;
           background:url(S:/Image for Project/Background1.avif)
           
        }
        /* .client-item-{
            height: 102px;
            padding: 0px;
            align-items: center;
            justify-items: center;

        } */
         .box center img{
            align-items: center;
            justify-items: center;
         }
        

    </style>
</head>

<body>
    <nav id="navbar">

        <div class="log">
            <img src="S:\Image for Project\Logot.jpeg" alt="">
        </div>

        <ul>
            <li class="item"><a href="#"">Home</a></li>
        <li class=" item"><a href="#"">Contect Us</a></li>
        <li class=" item"><a href="#"">Service</a></li>
        <li class=" item"><a href="#"">About Us</a></li>
        </ul>
    </nav>
    <section id="home">
                                <h1 class="h-primary">Welcom To MyOnlineFuBu</h1>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas fuga at
                                    praesentium, vel suscipit voluptatum non dolorum soluta qui laboriosam?</p>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione mollitia sapiente aperiam, tempore veniam quia!</p>
                                    <button class="btn">Order Now</button>
                                </section>

                                <section class="services-cotener">
                                    <h1 class="h-primary">Our Services</h1>
                                    <div id="services">
                                       <div class="box center">
                                        <img src="S:\Image for Project\Ear ring3.jpeg" alt="">
                                        <h2 class="h-secondery">Slk Silver</h2>
                                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolor cum nobis pariatur!</p>
                                       </div>


                                       <div class="box center">
                                        <img src="S:\Image for Project\Ear ring.webp" alt="">
                                        <h2 class="h-secondery">Silver</h2>
                                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolor cum nobis pariatur!</p>
                                       </div>
                                    
                                    
                                    
                                       <div class="box center">
                                        <img src="S:\Image for Project\earring4.jpeg" alt="">
                                        <h2 class="h-secondery">Silk Gold</h2>
                                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolor cum nobis pariatur!</p>
                                       </div>
                            
                                </section>
<section id="client-section">
    <h1 class="h-primary center">Our Client</h1>
    <div class="client">
        <div class="client-item">
            <img src="S:/Image for Project/X logo.jpeg"alt="Our client">
        </div>
        <div class="client-item">
            <img src="S:/Image for Project/microsoft.png"alt="Our client">
        </div>
        <div class="client-item">
            <img src="S:/Image for Project/fb logo.png"alt="Our client">
        </div>
        <div class="client-item">
            <img src="S:/Image for Project/Instagram.jpeg"alt="Our client">
        </div>
    </div>
</section>

                                </section>
                               
</body>

</html>
