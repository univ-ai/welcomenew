---
title: "AI-1 A" 
permalink: /aiexpress/ai1a/
kind: course
excerpt: Linear and Logistic Regression
sequence: 1
header:
  overlay_image: /assets/images/header/HeaderDesign2.jpeg
  teaser: /assets/images/header/HeaderDesign2.jpeg
---

<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
<!-- -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js" integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s" crossorigin="anonymous"></script>
<style>
  .modal-margin {
    margin: 0 auto;
  }
  .modal {
    background: transparent;
  }
  .ta-img {
    zoom:55%; 
    border: 1px solid black; 
    border-radius: 2em; 
    margin-right: 1em; 
    height:225px;
  }
  .circular--portrait { 
    width: 5.7rem; 
    height: 5.7rem; 
    overflow: hidden; 
    border-radius: 50%; 
    } 
  .circular--portrait-img { 
    width: 100%; 
    height: auto; 
    }
  .img-border {
    border-left: 1px solid #787D80;
    border-top: 1px solid #787D80;
    border-radius: 50%;
    padding: 0.5rem;
  }
  .img-border:hover {
    box-shadow: -3px 3px #787D80, -2px 2px #787D80, -1px 1px #787D80;
  }
  @media (max-width: 630px) {
    .circular--portrait { 
    width: 2.5rem; 
    height: 2.5rem; 
    overflow: hidden; 
    border-radius: 50%; 
    } 
  }
  .circular-portrait-instructor { 
    width: 12rem; 
    height: 12rem; 
    overflow: hidden; 
    border-radius: 20%; 
    display: block;
    } 
  .circular-portrait-instructor-img { 
    width: 100%; 
    height: auto; 
    }
  .img-border-instructor {
    border-left: 1px solid #787D80;
    border-top: 1px solid #787D80;
    border-radius: 20%;
    padding: 0.5rem;
    position: relative;
  }
  .img-border-instructor:hover {
    box-shadow: -3px 3px #787D80, -2px 2px #787D80, -1px 1px #787D80;
  }
  @media (max-width: 630px) {
    .circular-portrait-instructor { 
    width: 2.5rem; 
    height: 2.5rem; 
    overflow: hidden; 
    border-radius: 50%; 
    } 
  }
  .instructor-overlay {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    background: rgba(0,0,0,0.6);
    color: #ffffff;
    border-radius: 20%; 
    font-family: 'Quicksand', sans-serif;
    font-size: 1em;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    opacity: 0;
    transition: opacity 0.25s;
  }

  .instructor-overlay > * {
    transform: translateY(20px);
    transition: transform 0.25s;
  }

  .instructor-overlay:hover {
    opacity: 1;
  }

  .instructor-overlay:hover > * {
    transform: translateY(0);

  }

 
  .instructor
  .instructor-overlay-title {
    font-weight: bold;
  } */
  
</style>


<!-- TA Modal Section -->
<style>
  .modal-margin {
    margin: 0 auto;
  }

  .modal {
    background: transparent;
  }
</style>

<!-- TA Modal 1--> 
<div class="container">
<div class="modal fade modal-margin" id="Arya" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Arya Mohan</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <center><img src="/assets/images/people/AryaMohan.jpeg" alt="Arya" style="height:200px;margin-right:15px;"></center>
        <ul style="list-style:circle; padding-left: 2em;">
          <li>Arya is working as a research and teaching fellow with Univ.AI.</li>
          <li>Previously, she was a data analyst at Schneider Electric.</li>
          <li>She is currently working as a research fellow at the StellarDNN lab.</li>
        </ul>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#Arya').appendTo('body');
</script>

<!-- TA Modal 2-->
<div class="container">
<div class="modal fade modal-margin" id="Shibani" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Shibani Budhraja</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/ShibaniBudhraja.png" alt="Shibani" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>A Psychologist and amateur  musician exploring the world of Data Science.</li>
<li>Her current and future goals include working towards mastering Reinforcement Learning along with exploring ethics and biases in AI.</li>
<li>Her previous occupations have included a few hospital internships under neuropsychologists and psychiatrists , teaching at a  NGO for young girls and thereafter teaching kids with special needs.</li>
</ul>
</div>
</div>
</div>
</div>
</div>
<script>
     $('#Shibani').appendTo('body');
</script>

<!-- TA Modal 3-->
<div class="container">
<div class="modal fade modal-margin" id="VishnuModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Vishnu M</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <center><img src="/assets/images/people/VishnuM.png" alt="Vishnu" style="height:200px;margin-right:15px;"></center>
        <ul style="list-style:circle; padding-left: 2em;">
          <li>Vishnu is the Program Coordinator for academic operations at Univ.AI.</li>
          <li>He is a Computer Vision enthusiast and has recently completed his undergraduation from JECRC University, Jaipur.</li>
          <li>Currently, he is also working as a research assistant in the StellarDNN lab at Harvard, where he is working on the intersection of Deep Learning and Astronomy.</li>
        </ul>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#VishnuModal').appendTo('body');
</script>

<!-- TA Modal 4-->
<div class="container">
<div class="modal fade modal-margin" id="AnshikaModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Anshika Gupta</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/AnshikaGupta.png" alt="Anshika" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Anshika is the Co-ordinatior of Academic Development at Univ.AI.</li>
<li>She is a deep learning enthusiast and a recent undergraduate from JECRC University, Jaipur.</li>
<li>Previously, she was a Research Intern at Neos HealthTech where she worked on developing algorithms for medical image analysis and segmentation.</li>
</ul>
</div>
</div>
</div>
</div>
</div>
<script>
     $('#AnshikaModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="Lakshay" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Lakshay Chawla</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/LakshayChawla.png" alt="Lakshay" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Lakshay is a final year CSE undergrad at MAIT, Delhi.</li>
<li>Eventual goals include unravelling the mysteries of deep space with the help of ever-evolving AI.</li>
<li>You might find him engrossed in music and never-ending thoughts if not working for the future.</li>
</ul>
</div>
</div>
</div>
</div>
</div>
<script>
     $('#Lakshay').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="PavlosModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Pavlos Protopapas</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="https://github.com/hargun3045/blog-dump/blob/master/pavlos-website/pavlosimage.jpeg?raw=true" alt="Pavlos" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Scientific Director of the Institute for Applied Computational Science (IACS).</li>
<li>Teaches Introduction to Data Science (<a href="https://harvard-iacs.github.io/2019-CS109A/">CS109a</a>), Advanced Topics in Data Science (<a href="https://harvard-iacs.github.io/2020-CS109B/">CS109b</a>) and Advanced Practical Data Science (<a href="https://harvard-iacs.github.io/2021-AC215/">AC215</a>).</li>
<li>He is a leader in astrostatistics and he is excited about the new telescopes coming online in the next few years.</li>

You can <a href="https://www.univ.ai/team/pavlos-protopapas-2">read more about him here</a>.
</ul>
</div>
</div>
</div>
</div>
</div>
<script>
     $('#PavlosModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="IgnacioModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
<div class="modal-dialog" role="document">
<div class="modal-content">
<div class="modal-header">
<h5 class="modal-title" id="exampleModalLabel">Ignacio Becker</h5>
<button type="button" class="close" data-dismiss="modal" aria-label="Close">
<span aria-hidden="true">X</span>
</button>
</div>
<div class="modal-body">
<center><img src="/assets/images/people/IgnacioBecker.jpeg" alt="Ignacio" style="height:200px;margin-right:15px;"></center>
<ul style="list-style:circle; padding-left: 2em;">
<li>Astronomer currently pursuing a Ph.D. in Computer Science at Pontificia Universidad Católica in Chile. </li>
<li>His main area of research is applied AI to astrophysical problems. </li>
<li>Nowadays, he focuses on developing models to process the real-time data of the next generation of telescopes.</li>

</ul>
</div>
</div>
</div>
</div>
</div>
<script>
     $('#IgnacioModal').appendTo('body');
</script>


<!-------------------------------------------------------------------------------------------------------------------------->

>*Statistics. Math. Computer Science. Physics. Long ago, the four disciplines lived together in harmony. Then, everything changed when the Computer Science attacked. Only a master of all four elements, could stop them, but when the world needed it most, it was not invented. A few years ago the world  discovered the new master, a  scientist called data scientist, a master of all four elements.*

Welcome to AI-1 A! 
The objective of this module is to provide fundamental understandings of machine learning models 
and get you working with the basic concepts of ML and AI. 

You will start with the basic regression models (KNN, Linear, Multi, Poly), classification models (kNN, Logistic). Along the way, you will operationalize the key concepts of machine learning: picking the right complexity, preventing overfitting, regularization, and model evaluation. 

At the end of this module, you will be able to run basic and advanced machine learning models, and tell how well they are performing. 

This page introduces you to the team, the basic instructions, the schedule and various elements of our class.

## The Team

*Click on avatars of the team to know more about them.*

### Instructors

<div style="display: grid; grid-template-columns: repeat(4, 1fr);">

  <div class="img-border-instructor" style="grid-column: 1/2;">
    <div class="circular-portrait-instructor">
      <img src="https://github.com/hargun3045/blog-dump/blob/master/pavlos-website/pavlosimage.jpeg?raw=true" class="circular-portrait-instructor-img" align="left" style="margin-top:-30px;" data-toggle="modal" data-target="#PavlosModal"/>
    </div>
    <div class="instructor-overlay" data-toggle="modal" data-target="#PavlosModal">
      <p class="instructor-overlay-title">
        Pavlos Protopapas
      </p>
    </div>
  </div>
  
  <div class="img-border-instructor" style="grid-column: 3/4;">
    <div class="circular-portrait-instructor">
      <img src="/assets/images/people/IgnacioBecker.jpeg" class="circular-portrait-instructor-img" align="left" data-toggle="modal" data-target="#IgnacioModal"/>
    </div>
    <div class="instructor-overlay" data-toggle="modal" data-target="#IgnacioModal">
      <p class="instructor-overlay-title">
        Ignacio Becker
      </p>
    </div>
  </div>
</div>

### Teaching Assistants

<div style="display: grid; grid-template-columns: repeat(10, 1fr);">

  <div class="img-border" style="grid-column: 1/2;">
    <div class="circular--portrait">
      <img src="/assets/images/people/AryaMohan.jpeg" class="circular--portrait-img" align="left" style="margin-top:-15px;" data-toggle="modal" data-target="#Arya"/>
    </div>
  </div>

  <div class="img-border" style="grid-column: 3/4;">
    <div class="circular--portrait">
      <img src="/assets/images/people/VishnuM.png" class="circular--portrait-img" align="left" style="margin-top:-15px;" data-toggle="modal" data-target="#VishnuModal"/>
    </div>
  </div>

  <div class="img-border" style="grid-column: 5/6">
    <div class="circular--portrait">
      <img src="/assets/images/people/AnshikaGupta.png" class="circular--portrait-img" align="left" style="margin-top:-15px;" data-toggle="modal" data-target="#AnshikaModal"/>
    </div>
  
  </div>

  <div class="img-border" style="grid-column: 7/8;">
    <div class="circular--portrait">
      <img src="/assets/images/people/ShibaniBudhraja.png" class="circular--portrait-img" align="left" data-toggle="modal" data-target="#Shibani"/>
    </div>
  </div>

  <div class="img-border" style="grid-column: 9/10">
    <div class="circular--portrait">
      <img src="/assets/images/people/LakshayChawla.png" class="circular--portrait-img" align="left" data-toggle="modal" data-target="#Lakshay"/>
    </div>
  </div>

  

</div>


<br>

## The Coursework

We have very carefully designed the coursework to give you, the student, a wholesome learning experience.

Each week shall include:

- 2 Sessions
- 2 Labs
- Office hours

### Session - What to expect

![](/assets/images/Session.png)

The course includes two 1.5 hour sessions per week. Before the session begins, students are expected to complete a pre-class reading assignment and and attempt a quiz based on the same.

A session will have the following pedagogy layout which will be repeated three times:

- Approx. 15 minutes of live online instruction followed by approx 15 minutes of Q/A + Quiz + Exercises. 
- Sessions will help students develop the intuition for the core concepts, 
 provide the necessary mathematical background, and provide guidance on technical details. 
- Sessions will be accompanied by relevant examples to clarify key concepts and techniques.

After the session, students are expected to complete a short post-class quiz based on the principal concepts covered in class.

### Lab - What to expect

![](/assets/images/Lab.png)

A lab is a TA driven 1.5 hour session that is divided into 3 major parts. 

- Each lab begins by revisiting the quizzes and exercises done in the previous lecture session. 

- After discussing exercises, we will have a semi-formal Q/A session. All doubts pertaining, but not limited, to the previous session are welcome.


![](/assets/aiexpress/ai1a.assets/Content.png)

### Course Pre-Requisites 

Your are expected to have a working knowledge of python, along with these three libraries:

- Numpy
- Pandas
- Matplotlib

All exercises in this course will be done in jupyter notebooks. 

> Note: No prior knowledge of machine learning libraries is necessary for this module

Before you begin the course, we have prepared for you a simple exercise to ensure your proficieny of the above libraries. 

This will help you assess your preparedness for the course, and will also help you familiarize yourself with the platform.

## Diversity & Inclusion

We actively seek and welcome people of diverse identities, from across the spectrum of disciplines and methods since Artificial Intelligence (AI) increasingly mediates our social, cultural, economic, and political interactions [1]. 

We believe in creating and maintaining an inclusive learning environment where all members feel safe, respected, and capable of producing their best work. 

We commit to an experience for all participants that is free from -- Harassment, bullying, and discrimination which includes but is not limited to:

- Offensive comments related to age, race, religion, creed, color, gender (including transgender/gender identity/gender expression), sexual orientation, medical condition, physical or intellectual disability, pregnancy, or medical conditions, national origin or ancestry.
- Intimidation, personal attacks, harassment, unnecessary disruption of talks during any of the learning activities.

Reference: 

[1] K. Stathoulopoulos and J. C. Mateos-Garcia, “Gender Diversity in AI Research,” SSRN Electronic Journal, 2019 [Online]. Available: [http://dx.doi.org/10.2139/ssrn.3428240](https://dx.doi.org/10.2139/ssrn.3428240).


<style>
table {
  font-family: Arial, Helvetica, sans-serif;
  border-collapse: collapse;
  width: 100%;
  border-top: 0px solid black;
  border-bottom: 0px solid black;
}

td, th {
  border: 1px solid #ddd;
  padding: 8px;
}
tr:nth-child(even){background-color: #ffffff;}
tr:nth-child(odd){background-color: #ffffff;}
th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: #848484;
  color: white;
}
ul {
  margin-top: 0;
  margin-bottom: 0;
}
</style>