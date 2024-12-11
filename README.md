<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Portfolio</title>
   
   
   
   <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #ecf0f1, #156872);
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            
        }
        
        


         .content-with-image {
          display: flex;
          align-items: center;
          gap: 20px;
          margin-bottom: 20px;
           text-align: left;
        }
         .content-with-image img {
          max-width: 30%; 
          height: auto;
          border-radius: 8px; 
          box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1); 
        }


         .content-with-image p {
         flex: 1; 
         font-size: 1em;
         line-height: 1.8em;
         color: #2c3e50;
          margin: 0;
        }
         .content-with-image.reverse {
         flex-direction: row-reverse;
        }

        image img{
            max-width: 50%;
            height: auto;
            margin: 20px auto;
            text-align: center;

        }

       







        header {
            width: 80%;
            background-color: #ffffff;
            border-radius: 8px;
            text-align: center;
            padding: 40px 20px;
            margin: 20px 0;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2.5em;
            margin-top: 0px;
            padding-bottom: 0px;
            color: #2c3e50;
        }

        header h2 {
            font-size: 1.5em;
            margin-top: 0px;
            padding-bottom: 10px;
            color: #2c3e50;
        }

        nav {
            margin-top: 0px;
        }

        nav button {
            padding: 10px 20px;
            margin: 5px;
            background-color: #3498db;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            transition: background-color 0.3s;
        }

        nav button:hover {
            background-color: #2980b9;
        }




        
        /* Main Content Section */
        main {
            width: 80%;
            background-color: #ffffff;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }
    




        .bodyparagraph {
            background-color: #ecf0f1;
            padding: 40px;
            margin-bottom: 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 1px 5px rgba(0, 0, 0, 0.05);
        }
        
        .bodyparagraph h4{
            margin-top: 0%;
            font-size: x-large;
        }
        .bodyparagraph h5{
            margin-top: 0%;
            font-size: x-large;
        }
        .bodyparagraph h3{
            margin-top: 0%;
            font-size: x-large;
        }
       
        .bodyparagraph h6{
            margin-top: 0%;
            margin-bottom: 3%;
            font-size: x-large;
        }

        .bodyparagraph p {
            margin: 0;
            font-size: 1.1em;
            line-height: 1.8em;
        }


        




        footer {
            width: 80%;
            background-color: #ffffff;
            text-align: center;
            padding: 30px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            font-size: 0.9em;
            color: #555;
        }
    </style>
</head>





<body>
    <!-- Header Section -->
    <header>
        <h1>My Personal Portfolio</h1>
        <h2>“Never give up, for that is just the place and time that the tide will turn.” ―Harriet Beecher Stowe</h2>
        <nav>
            <button onclick="scrollToSection(0)">About Me</button>
            <button onclick="scrollToSection(1)">Art Journey</button>
            <button onclick="scrollToSection(2)">My Works</button>
            <button onclick="scrollToSection(3)">Reflection</button>
        </nav>
    </header>





    <main>
   
   
        <section class="bodyparagraph">
            <h4>About Me</h4>
            <p>I am Angela Huang, a high school student who is passionate about art and social impact. I especially love paintings and drawings; they are a powerful outlet for me to express my creativity. This portfolio is a selection of my artwork that showcases my artistic style. At the same time, it will also show you what inspired some of my work. For me, each painting is more than just an image - it is a journey of self-discovery and a personal interpretation of the world around me. In addition to art, I am committed to fostering communication and collaboration, both of which I believe are vital to creativity and community involvement. Through this portfolio, I hope to connect with like-minded individuals, share ideas, and continue to grow through meaningful interactions and collaborative opportunities.</p>
        </section>
        <section class="bodyparagraph">
            <h5>Art Journey</h5>
            <p> Among my various hobbies, dancing, playing piano and badminton are my greatest passions. I have loved capturing my imagination on paper since I was a child. I often fill my textbooks with countless sketches. Despite my passion for drawing, I have had my fair share of frustrations. My drawings were often criticized for being unattractive and unrefined, ridiculed by my classmates, and even torn to shreds when I was bullied. Teachers were also dismissive of my efforts, calling my work derivative and uninspired.
                As a child, I internalized these criticisms, choosing silence over confrontation, and took my emotions out on my artwork. Painting became my refuge - a place where I could escape judgment and pour out my thoughts and feelings. While I may not have received notable accolades in this field, the act of creating remains a deeply personal experience for me. Each of my paintings epitomizes my emotions and is both a reflection of my inner world and a testament to my resilience.</p>
        </section>
        <section class="bodyparagraph">
            <h3>My Works</h3>


            <div class="content-with-image">
                <img src="手机.jpg" alt="Artwork 1">
                <p>I created this painting in my relatively early days. The drawing is of a cell phone screen. I was inspired by another artist while creating this drawing. Combining ghosts and angels. Using greyish solids to bring out the vibrancy when the colors are similar.</p>
            </div>
            
        
            



        
            <div class="content-with-image reverse">
                <img src="雨伞海洋.jpg" alt="Artwork 2">
                <p>This image was created during the first period after my painting progressed. By this time I had made tremendous progress in composition and background design compared to before. The design of the sea and the umbrellas shows the diversity of the seabed. These details add greatly to the layering of the work.</p>
            </div>
           
           
           
           
           

            <div class="content-with-image">
                <img src="冰淇淋.jpg" alt="Artwork 3">
                <p>This image was inspired by a drawing I had as a child. Re-created that one drawing to be exact. So the sun and sky are represented in the background in a child's way. In the front I refined the design of the matchmaker from my childhood to make the image richer.</p>
            </div>
           
           
           
           
           
           
            <div class="content-with-image reverse">
                <img src="四格.jpg" alt="Artwork 4">
                <p>I created this piece the previous year. At that time I was quite depressed, so the overall tone of the picture is on the gray side. When designing this character, I thought she should be more relevant to our lives. So there wasn't much creativity in her. Several important periods in her life are shown in these four short images.</p>
            </div>



            <div class="content-with-image">
                <img src="三.jpg" alt="Artwork 5">
                <p>This same photo was created at the time when the character design was being created. This picture spawned more life oriented drawings of the character. Like selling fish, and delivering books home. The idea was to show more of the characterization of the character.</p>
            </div> 
           
           


           
            <div class="content-with-image reverse">
                <img src="蘑菇.jpg" alt="Artwork 5">
                <p>This last picture is one I drew this year. In this picture by shrinking the figure, and not shrinking the figure. The visual impact of miniaturization is realized. At the same time, I also learned how to use the relationship between reality and falsehood and the distinction between warm and cool colors more subtly. The overall warm color of this image shows the energy and warmth of the scene.</p>
            </div> 



           


        </section>        
       
        <section class="bodyparagraph">
            <h6>Reflection</h6>
            <p>Although I've meandered my way through painting, as something I love. I think it would be a shame to give it up. Though I don't think what I create is necessarily refined, good art. But I do think art carries a story rather than a presentation. So as a hobby, don't worry too much about what other people see, and as something you really love don't give it up so easily. Not everything is smooth sailing. The most important thing is to stick to your heart. Finally thank you for reading my portfolio. </p>
        </section>
   
   
   
    </main>



    <footer>
        <p>&copy; 2024 My Personal Portfolio </p>
    </footer>





    <script>
        function scrollToSection(index) {
            const sections = document.querySelectorAll('.bodyparagraph');
            if (sections[index]) {
                sections[index].scrollIntoView({ behavior: 'smooth' });
            } else {
                console.error('Section not found at index:', index);
            }
        }
    </script>
</body>
</html>
