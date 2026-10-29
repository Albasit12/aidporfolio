<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    * {margin:0;
      padding:0;
      box-sizing: border-box;
    }
    body {background-color: goldenrod; color:#333;}
    a {text-decoration:none; color: inherit;}

    .navbar {
      background: blue;
      color:white;
      width: 150vw;
      display:flex;
      justify-content:space-between;
      align-items:center;
      position:sticky;
      top:0;
      z-index:1000;
    }
    .navbar ul {list-style: none; display:flex; gap:1.5rem;}
    .navbar a {color:white; font-weight:500;}
    #dashboard{
      align-items: center;
      text-align: center;
      margin-bottom: 20px;
    }
    #dashboard button{
      flex-direction: column;
      padding: 1rem 2rem;
      justify-content: center;
       background:#ff6b35;
       border-radius: 10px;
       cursor: pointer;
       }
    .pic{
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 20px;
    }
    .pic img{
      border-radius: 50%;
      border: 4px solid #fff;
    }
  p{
      background:white; padding:1.5rem; border-radius:10px;
      box-shadow:0 4px 8px rgba(0,0,0,0.1);}
   #projects{padding:4rem 2rem; text-align:center;
     margin-top: 10px;
     margin-bottom: 20px;
   } 
 h2{margin-bottom: 0.5rem;color: white; text-align: center;
   font-size: 40px;
}
       .pro{
      background: white; padding: 1.5rem; border-radius:20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        margin-top: 20px;
       }
       .link-btn {
  /* Size */
  padding: 12px 28px;
  
  /* Color */
  background-color: #007bff;
  color: #ffffff;
  
  /* Shape */
  border: none;
  border-radius: 8px;
  
  /* Text */
  font-size: 16px;
  font-weight: 600;
  font-family: Arial, sans-serif;
  
  /* Behaviour */
  cursor: pointer;
  transition: all 0.3s ease;
}

.link-btn:hover {
  background-color: #0056b3;
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

.link-btn:active {
  transform: scale(0.97);
}
    .contact {padding:4rem 2rem; text-align:center;}
    .contact form {max-width:500px; margin:auto; display:flex; flex-direction:column; gap:1rem;}
    .contact input, .contact textarea {
      height: 50px;
      width:100%; border:1px solid #ccc; border-radius:6px;
    }
    .contact button {
      background:#ff6b35; color:white; padding:0.75rem; border:none; border-radius:6px; cursor:pointer;
    }
</style>
  <title></title>
</head>

<body>
  <section class="nav">
    <nav class="navbar">
<h1>AID Portfolio</h1>
      <ul>
        <li><a href="#dashboard">Dashboard</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
        
      </ul>
    </nav>
  </section>
  <section id="dashboard">
    <h2> Welcome to my portfolio </h2> <br/>
    <button> Explore </button>
  </section>
  
  <div class="pic">
    <img width="150px" height="150px auto" src="/profile-pic.jpg" alt="profile-pic" class="profile-picture"></div></br>
    <h2>About Me</h2>
    <p><strong>I'm Abdulbasit Lamidi and I'm a Graphic Designer and a Passionate Frontend Website Developer</strong> <br>I help individual,Businesses Organisation and Company to craft and build real time responsive website that stooth their ideas about there business thereby bring it to life.</p>
  </div>
  <div id="projects">
    <h2> MY PROJECTS </h2>
     <P>As a Beginner I strongly Believe That
     You Don't Have to 
     Wait Until you Know All Just Start Building With The Knowledge You Have, Keep learning and Stay Consistent "Beware that one of the greatest enemy of man is Procrastination".So you have to fight the fear and come out of your shadow.</P>
  </div>
      <div class="pro">
        <h4 style="color:#fff">Counter</h4>
        <p>Tapping the count makes the number start counting and when reset it goes back to zero.
            <button onclick="window.location.href ='/other /count.html'"> check it</button></p>
      </div>
            <div class="pro">
        <h4 style="color:#fff">My-To-Do-List</h4>
        <p>A simple To-Do-List that can help by planning task for a day it's a beginner project.
             <button onclick="window.location.href ='/other /my to do list.html'"> check it</button></p>
      </div>
      <div class="pro">
        <h4 style="color:#fff">Background Changer</h4>
        <p>Tapping each buttons change the background color with name of the color inscribed on the button unless random that changes to different varieties of colors.
             <button onclick="window.location.href ='/other /color.html'"> check it</button></p>
      </div>
            <div class="pro">
        <h4 style="color:#fff">Loading Animation</h4>
        <p>This i a simple loading page.
      <button onclick="window.location.href ='/other /loading.html'"> check it</button> </p>
      </div>
            <div class="pro">
        <h4 style="color:#fff">Simple Freelance Platform</h4>
        <p>As the name imply a simple beginners friendly freelance projects .
             <button onclick="window.location.href ='/other /freelance.html'" class="link-btn"> check it</button>
       </p>
      </div>
  </div>
   <section style="background: white">
     <h4>My Experience </h4>
     <ul>
       <li>HTML(HyperTextMarkupLanguage)</li>
       <li>CSS(Cascading Style Sheet)</li>
       <li>JavaScript And DOM(Document Object Model) Manipulation</li>
     </ul>
   </section>
  
  <section class="contact">
    <h2>Contact</h2>
    <form class="message">
      <input type="text" placeholder="Name" required>
      <input type="email" placeholder="Email" required>
      <textarea>write your message</textarea>
      <br /> <button onclick="submit">Send Message</button>
      
    </form>
  </section>
  <script>
        function scrollToSection(id) {
      document.getElementById(id).scrollIntoView({behavior:'smooth'});
  </script>
</body>

</html>
