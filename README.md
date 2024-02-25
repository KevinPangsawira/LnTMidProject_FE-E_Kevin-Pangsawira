# LnTMidProject_FE-E_Kevin-Pangsawira
midproject BNCC
![projectdummy3](https://github.com/KevinPangsawira/LnTMidProject_FE-E_Kevin-Pangsawira/assets/145685359/0fa2e496-732c-4c69-9c34-94ddd2a8d621)
![projectdummy2](https://github.com/KevinPangsawira/LnTMidProject_FE-E_Kevin-Pangsawira/assets/145685359/45688608-ea45-4abf-85ee-59a60c2a258a)
![projectdummy](https://github.com/KevinPangsawira/LnTMidProject_FE-E_Kevin-Pangsawira/assets/145685359/5478c033-ebfb-47a7-9c2a-2dbdb4ebfdd2)
![binusfoto](https://github.com/KevinPangsawira/LnTMidProject_FE-E_Kevin-Pangsawira/assets/145685359/af216ed6-394f-4669-b9e2-7d97e904d242)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <marquee behavior="action" scrollamount="10">
            <h1>Welcome to Portofolio <nama></h1>
        </marquee>
    </header>
    <div class="kevin">Kevin Pangsawira</div>
    <div class="container">
        <section class="about-me">
            <img src="binusfoto.jpg" alt="Foto Diri">
            <div class="description">
                <p style="20px">Deskripsi mengenai diri kamu</p>
                <table>
                    <tr>
                        <th>Tahun</th>
                        <th>Deskripsi Pendidikan</th>
                    </tr>
                    <tr>
                        <td>2010</td>
                        <td>SD</td>
                    </tr>
                    <tr>
                        <td>2013</td>
                        <td>SMP</td>
                    </tr>
                    <tr>
                        <td>2016</td>
                        <td>SMA</td>
                    </tr>
                    <tr>
                        <td>2020</td>
                        <td>S1</td>
                    </tr>
                </table>
                <p>Berpengalaman sebagai UX Designer dan Creative User Interface Designer serta hardskill seperti editing dan menggambar</p>
            </div>
        </section>
        <section class="portfolio">
            <div class="project">
                <!-- <img src="projectdummy.png" alt="Project 1"> -->
                <font style="font-size: 35px; font-weight: bold;">
                  Experience  
                </font>
                <br>   
                <p style="font-size: 13px; font-family:'Times New Roman', Times, serif;">
                    <font style="font-weight: bold;">Senior Ux Designer (2014-2016)</font>
                    <br><br>
                    <font style="font-size: 20px;">Company Name/ Location</font>
                    
                    <br><br>
                    <font color="gray" style="font-size: 15px;">Lorem ipsum is simply dummy text of the printing and 
                    typesetting 
                    industry. Lorem I has been the industry's standart</font>
 
                </p>
                <img src="projectdummy2.jpeg" alt="project">

                <p style="font-size: 13px; font-family:'Times New Roman', Times, serif;">
                    <font style="font-size: 20px;">Creative User Interface Designer (2016-Present)</font>

                    <br><br>
                    Company Name/ Location
                    <br><br>
                    <font color="gray" style="font-size: 15px;">Lorem ipsum is simply dummy text of the printing and 
                    typesetting 
                    industry. Lorem I has been the industry's standart</font>
                    <br><br>
                    <img src="projectdummy3.jpeg" alt="project"> 
                    <br><br><br>
                    <font style="font-size: 25px; font-weight: bold;">
                        Pro Skills
                    </font>
                    <div class="allskill">
                            <div class="proskill">
                            <font style="font-size: 15px;">Photoshop</font>
                                <div id="levelbox1">
                                    <div id="levelline1">
                                    </div>
                                </div>

                            </div>
                            <div class="proskill">
                                <font style="font-size: 15px;">Illustrator</font>
                                    <div id="levelbox2">
                                        <div id="levelline2">
                                        </div>
                                    </div>
    
                                </div>
                                <div class="proskill">
                                    <font style="font-size: 15px;">Indesign</font>
                                        <div id="levelbox3">
                                            <div id="levelline3">
                                            </div>
                                        </div>
                
        
                                    </div>  

                                    <div class="proskill">
                                        <font style="font-size: 15px;">After effect</font>
                                            <div id="levelbox4">
                                                <div id="levelline4">
                                                </div>
                                            </div>
            
                                        </div>
                                        <div class="proskill">
                                            <font style="font-size: 15px;">Sketch</font>
                                                <div id="levelbox5">
                                                    <div id="levelline5">
                                                    </div>
                                                </div>
                
                                            </div>
                    </div>
                   
               
                </p>

               
             
                
            </div>
           
        </section>
        <section class="contact">
            <h2>Contact</h2>
            <form action="">
                <input type="text" placeholder="Nama Lengkap">
                <input type="email" placeholder="Email">
                <input type="text" placeholder="LinkedIn">
                <textarea placeholder="Comment"></textarea>
                <button type="submit">Submit</button>
            </form>
        </section>
    </div>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: black;
    color: #fff;
    padding: 20px;
    text-align: center;
    animation: Scale 5s infinite ease-in-out;
    
}

.container {
    max-width: 1200px;
    margin: auto;
    padding: 20px;
}

.about-me {
    /* display: flex; */
    justify-content: space-between;
    margin-top: 20px;
}

.about-me img {
    width: 200px;
    height: 250px;
    padding-left: 20px;
    /* border-radius: 50%; */
}

.about-me .description {
    flex: 1;
    margin-left: 20px;
}

.about-me table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
}

.about-me table th, .about-me table td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: left;
}

.portfolio {
    font-size: 20px;
    margin-top: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.portfolio .project {
    padding-left: 5%;
    flex-basis: calc(33.33% - 20px);
    margin-bottom: 20px;
}

.portfolio .project img {
    width: 100%;
    height: auto;
}

.contact {
    margin-top: 20px;
}

.contact form {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: space-between;
}

.contact form input, .contact form textarea {
    width: calc(50% - 10px);
    padding: 10px;
    margin-bottom: 10px;
}

.contact form button {
    width: 20%;
    padding: 10px;
    background-color: #333;
    color: #fff;
    border: none;
    cursor: pointer;
}

img{
    animation: translate 1s ease-in-out;
}

@media screen and (max-width: 768px) {
    .contact form input, .contact form textarea {
        width: 100%;
    }
}

button:hover{
    animation: Scale2 infinite 1s ;
}
@keyframes Scale {
    0%,100% {
    }
    50% {
        background-color: white;
        color: black;
    }
}

@keyframes translate {
    0%,100% { 
        transform: translate(0px);
    }
    
    50% {
        transform: translate(180px);
        
       
    }
}

@keyframes Scale2 {
    0%,100% {
        transform: scale(1.2);
    }
    /* 50%{
        transform: scale(1.2);
    } */
}


#levelbox1 {
    width: 100px;
    height: 3px; 
    border: 1px solid #000; 
    position: relative;
    top: 4px;
    left: 35px;
    
    
  }

  #levelbox2 {
    width: 100px;
    height: 3px; 
    border: 1px solid #000; 
    position: relative;
    top: 4px;
    left: 45px;
    
    
  }
  #levelbox3 {
    width: 100px;
    height: 3px; 
    border: 1px solid #000; 
    position: relative;
    top: 4px;
    left: 50px;
    
    
  }
  #levelbox4 {
    width: 100px;
    height: 3px; 
    border: 1px solid #000; 
    position: relative;
    top: 4px;
    left: 35px;
    
    
  }
  #levelbox5 {
    width: 100px;
    height: 3px; 
    border: 1px solid #000; 
    position: relative;
    top: 4px;
    left: 62px;
    
    
  }
  
  #levelline1 {
    position: absolute;
    top: 0;
    left: 75%;
    width: 2px; 
    height: 100%; 
    background-color: #000; 
  }
  #levelline2 {
    position: absolute;
    top: 0;
    left:  60%;
    width: 2px; 
    height: 100%; 
    background-color: #000; 
  }
  #levelline3 {
    position: absolute;
    top: 0;
    left: 75%;
    width: 2px; 
    height: 100%; 
    background-color: #000; 
  }
  #levelline4 {
    position: absolute;
    top: 0;
    left: 75%;
    width: 2px; 
    height: 100%; 
    background-color: #000; 
  }
  #levelline5 {
    position: absolute;
    top: 0;
    left: 60%;
    width: 2px; 
    height: 100%; 
    background-color: #000; 
  }
  .proskill{
    display: flex;
    /* flex-direction: column;
    flex-wrap: wrap; */
    margin-bottom: 10px;
  }

  .allskill{
    display: flex;
    flex-direction: column;
    

  }

  .kevin{
    font-weight: bold;
    font-size: 25px;
    padding-left: 126px;
    position: absolute;
    margin-top: 10px;  
  }
