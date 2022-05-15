---
title: "Uncourse" 
permalink: /uncourse/
sequence: 1
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
    .register-button {
        background-color: #324bd9;
        border: none;
        color: white;
        padding: 20px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        border-radius: 12px;
    }
    .area:hover {
        cursor: pointer;
    }
</style>    

Uncourse is a series of workshops that we conduct for our students for them to learn skills that are not covered in the sessions, but are important to learn in order to excel in the field of data science and AI.

Here is the current schedule for all our workshops.

*Click on the topic of the workshop to know more.*
<div class="container">

<img src="/assets/uncourse.assets/schedule.png" alt="Workplace" usemap="#workmap" width="956" height="836">

<!-- <img src="index.assets/stellardnn.png" alt="Workplace" usemap="#workmap" width="800" height="400"> -->

<map name="workmap">
  <area shape="rect" class="area" coords="638,64,934,124" alt="SQL1" title="SQL 1" data-toggle="modal" data-target="#Sql1Modal">
  <area shape="rect" class="area" coords="638,124,934,186" alt="SQL2" title="SQL 2" data-toggle="modal" data-target="#Sql2Modal">
  <area shape="rect" class="area" coords="638,189,934,250" alt="Github" title="Github" data-toggle="modal" data-target="#GithubModal">
  <area shape="rect" class="area" coords="638,250,934,313" alt="Tensorboard" title="Tensorboard" data-toggle="modal" data-target="#TbModal">
  <area shape="rect" class="area" coords="638,313,934,375" alt="React" title="React" data-toggle="modal" data-target="#ReactModal">
  <area shape="rect" class="area" coords="638,375,934,439" alt="JAX" title="JAX" data-toggle="modal" data-target="#JaxModal">
  <area shape="rect" class="area" coords="638,439,934,503" alt="DSA1" title="DSA1" data-toggle="modal" data-target="#Dsa1Modal">
  <area shape="rect" class="area" coords="638,503,934,567" alt="DSA2" title="DSA2" data-toggle="modal" data-target="#Dsa2Modal">
  <area shape="rect" class="area" coords="638,567,934,631" alt="GNN" title="GNN" data-toggle="modal" data-target="#GnnModal">
  <area shape="rect" class="area" coords="638,631,934,692" alt="Spacy" title="Spacy" data-toggle="modal" data-target="#SpacyModal">
  <area shape="rect" class="area" coords="638,692,934,757" alt="Software Development" title="Software Development 1" data-toggle="modal" data-target="#Sd1Modal">
  <area shape="rect" class="area" coords="638,757,934,836" alt="Software Development" title="Software Development 2" data-toggle="modal" data-target="#Sd2Modal">
</map> 
</div>

<div class="container">
<div class="modal fade modal-margin" id="Sql1Modal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">SQL 1</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>We introduce you to relational databases, and sqlite in particular. The basics of SQL querying are covered, and contrasted with Pandas, thus establishing a common data access model for tabular data.</p>
        <center><h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px"><br><br>
        <h6>Timings</h6>
        <p>8:30 - 10:30 PM IST <br>
        (11:00 AM - 1:00 PM EST)</p> <br>
        <button class="register-button" onclick="location.href='https://us02web.zoom.us/meeting/register/tZcucu6pqD8qHtLZLS_yyVbZBcqr2ntDjDZY'">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#Sql1Modal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="Sql2Modal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">SQL 2</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>Building on SQL 1, this workshop dives into the "relational" part of databases. We cover indexes, joins, and subqueries, and offer some tips on when to use relational databases, and when to use NoSQL databases.</p>
        <center><h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>8:30 - 10:30 PM IST <br>
        (11:00 AM - 1:00 PM EST)</p> <br>
        <button class="register-button" onclick="location.href='https://us02web.zoom.us/meeting/register/tZwrf-2qqjMiH9b8Kqr1fKhU_y2W3AVlCV1b'">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#Sql2Modal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="TbModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Tensorboard</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>To be updated soon.</p>
        <center><h6>Instructor: Arya Mohan</h6>
        <img src="/assets/images/people/AryaMohan.jpeg" alt="Rahul" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>8:30 - 10:30 PM IST <br>
        (11:00 AM - 1:00 PM EST)</p> <br>
        <button class="register-button" onclick="location.href='https://us02web.zoom.us/meeting/register/tZcof-uorTwtHdZo1S-gO24CC4enY0MoFrWB'">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#TbModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="GithubModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">GitHub</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>This workshop gets you working with Git and GitHub, and shows you how to collaborate with 3 different workflow models: Direct, Branch based, and Fork based. The latter two workflows introduce pull requests to preserve the integrity of the main repository.</p>
        <center><h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>8:30 - 10:30 PM IST <br>
        (11:00 AM - 1:00 PM EST)</p> <br>
        <button class="register-button" onclick="location.href='https://us02web.zoom.us/meeting/register/tZ0ufumgqjMsGNW-nD3Pe_I4oxP4KQmly1YP'">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#GithubModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="ReactModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">React</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>In this workshop we focus on showcases machine learning models into a frontend app. We will go over integrating models for audio to text, text to audio, and Image classification into a frontend app. We will so work with plots in React and how to manage states(data) in the frontend. By the end of the workshop we would build a Neural Style Transfer App that looks like <a href="https://github.com/dlops-io/app-building-crashcourse/blob/main/app-building-crashcourse.png">this</a>.</p>
        <center><h6>Instructor: Shivas Jayaram</h6>
        <img src="/assets/images/people/ShivasJayaram.jpg" alt="Shivas" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>8:30 - 10:30 PM IST <br>
        (11:00 AM - 1:00 PM EST)</p> <br>
        <button class="register-button" onclick="location.href='https://us02web.zoom.us/meeting/register/tZYpcuygqTsuEtf8ZIS-8W4pH_IsXceOijaD'">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#ReactModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="JaxModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">JAX</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>JAX is a numpy replacement that provides automatic auto-differentiation of your code, without needing to use pytorch or tensorflow APIs. This is an advanced workshop going into differentiable programming and dynamic graphs.</p>
        <center><h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>8:30 - 10:30 PM IST <br>
        (11:00 AM - 1:00 PM EST)</p> <br>
        <button class="register-button" onclick="location.href='https://us02web.zoom.us/meeting/register/tZUscOChrDsuHNc4TpYCE-vMcwBgXIyWyFBa'">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#JaxModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="Dsa1Modal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Data Structures & Algorithms 1</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>This is the "interview" workshop. Using binary search and binary trees as examples, we analyse the complexity of algorithms and access methods on data structures.</p>
        <center><h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>8:30 - 10:30 PM IST <br>
        (11:00 AM - 1:00 PM EST)</p> <br>
        <button class="register-button" onclick="location.href='https://us02web.zoom.us/meeting/register/tZwud-yrrTItG9Ya47iPYhUvWQAM5cUHI4XY'">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#Dsa1Modal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="Dsa2Modal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Data Structures & Algorithms 2</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>To be updated soon.</p>
        <center><h6>Instructor: Kshitij Parwani</h6>
        <img src="/assets/images/people/KshitijParwani.png" alt="Rahul" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>8:30 - 10:30 PM IST <br>
        (11:00 AM - 1:00 PM EST)</p> <br>
        <button class="register-button" onclick="location.href='https://us02web.zoom.us/meeting/register/tZUrdeGuqTwqGdPewp-J1LK9C_1Abw__WzG9'">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#Dsa2Modal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="GnnModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Graph Neural Networks</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>Graph Neural Networks are all the rage today, enabling the learning of structured models in fields a different as protein structure and social networks. This workshop provides a simple introduction.</p>
        <center><h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>8:30 - 10:30 PM IST <br>
        (11:00 AM - 1:00 PM EST)</p> <br>
        <button class="register-button" onclick="location.href='https://us02web.zoom.us/meeting/register/tZYocuuvqjkvE9NL1UYNxmmL8-m-2hWL1RSp '">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#GnnModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="SpacyModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Spacy</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>Spacy is extensively used in industry for NLP tasks. This workshop will introduce you to training models using spacy for common NLP tasks.</p>
        <center><h6>Instructor: Yashraj Wani</h6>
        <img src="/assets/images/people/YashrajWani.png" alt="Yashraj" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>8:30 - 10:30 PM IST <br>
        (11:00 AM - 1:00 PM EST)</p> <br>
        <button class="register-button" onclick="location.href='https://us02web.zoom.us/meeting/register/tZYqdOqsrDgpHdXZP1y6Ppa0T-75Cf44dZdG'">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#SpacyModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="Sd1Modal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Software Development 1</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>We use the example of backpropagation in a Neural Network library to understand two key aspects of software development: <br>
        <b>(a)</b> the construction of a python library and <br>
        <b>(b)</b> refactoring code. <br>
        We will start with code written in a notebook and refactor it to a reusable python library.</p>
        <center><h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>8:30 - 10:30 PM IST <br>
        (11:00 AM - 1:00 PM EST)</p> <br>
        <button class="register-button" onclick="location.href='https://us02web.zoom.us/meeting/register/tZcvde6pqjsjH90GLItUbbwL6XmFVu3NJbzT '">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#Sd1Modal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="Sd2Modal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Software Development 2</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>To be updated soon.</p>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#Sd2Modal').appendTo('body');
</script>