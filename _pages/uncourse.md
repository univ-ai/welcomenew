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

Welcome to the second cycle of the series!

Here is the current schedule for all our workshops.

*(Click on the topic cell of the workshop table to know more)*
<div class="container">

<img src="/assets/uncourse.assets/schedule.png" alt="Workplace" usemap="#workmap" width="958" height="917">

<!-- <img src="index.assets/stellardnn.png" alt="Workplace" usemap="#workmap" width="800" height="400"> -->

<map name="workmap">
  <area shape="rect" class="area" coords="638,64,934,124" alt="Stream-lit" title="Stream-lit" data-toggle="modal" data-target="#Stream-litModal">
  <area shape="rect" class="area" coords="638,124,934,186" alt="Interview Coding Questions" title="Interview Coding Questions - 1" data-toggle="modal" data-target="#InterviewCodingQuestions_1Modal">
  <area shape="rect" class="area" coords="638,189,934,250" alt="Interview Coding Questions" title="Interview Coding Questions - 2" data-toggle="modal" data-target="#InterviewCodingQuestions_2Modal">
  <area shape="rect" class="area" coords="638,250,934,313" alt="Github" title="Github" data-toggle="modal" data-target="#GithubModal">
  <area shape="rect" class="area" coords="638,313,934,375" alt="PINNs" title="PINNs" data-toggle="modal" data-target="#PINNsModal">
  <area shape="rect" class="area" coords="638,375,934,439" alt="SQL1" title="SQL1" data-toggle="modal" data-target="#Sql1Modal">
  <area shape="rect" class="area" coords="638,439,934,503" alt="SQL2" title="SQL2" data-toggle="modal" data-target="#Sql2Modal">
  <area shape="rect" class="area" coords="638,503,934,567" alt="Tableau" title="Tableau" data-toggle="modal" data-target="#TableauModal">
  <area shape="rect" class="area" coords="638,567,934,631" alt="3DCNNs" title="3D CNNs" data-toggle="modal" data-target="#ThreeDCNNsModal">
  <area shape="rect" class="area" coords="638,631,934,692" alt="CV Workshop" title="CV Workshop" data-toggle="modal" data-target="#CVWorkshopModal">
  <area shape="rect" class="area" coords="638,692,934,757" alt="Double Descent" title="Double Descent" data-toggle="modal" data-target="#DoubleDescentModal">
  <area shape="rect" class="area" coords="638,757,934,836" alt="CNN Transformer" title="CNN Transformer" data-toggle="modal" data-target="#CNNTransformerModal">
  <area shape="rect" class="area" coords="638,822,934,915" alt="Continual Learning" title="Continual Learning" data-toggle="modal" data-target="#ContinualLearningModal">
</map> 
</div>

<div class="container">
<div class="modal fade modal-margin" id="Stream-litModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Stream-lit</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>We introduce you to Stream-lit, a quick open-source python framework for building web apps for your data science / ML projects.</p>
        <center><!--<h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px">--><br><br>
        <h6>Timings</h6>
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#Stream-litModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="InterviewCodingQuestions_1Modal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Interview Coding Questions 1</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>How to tackle some commonly encountered Interview Coding Questions interspersed with concrete examples, tips and suggestions.</p>
        <center><!--<h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px;">--><br><br>
        <h6>Timings</h6>
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#InterviewCodingQuestions_1Modal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="InterviewCodingQuestions_2Modal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Interview Coding Questions 2</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>This workshop dives further into the common Interview Coding Questions , building upon the previous session.</p>
        <center><!--<h6>Instructor: Cristobal Donoso-Oliva</h6>
        <img src="/assets/images/people/CristobalDonoso.jpg" alt="Cristobal" style="height:200px;margin-right:15px;">--><br><br>
        <h6>Timings</h6>
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#InterviewCodingQuestions_2Modal').appendTo('body');
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
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#GithubModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="PINNsModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">PINNs</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p> An introduction to Physics-Informed Neural Networks. As the name sugguests, these Deep Networks are informed by any given law in Physics (a nonlinear partial differential equation) to address supervised learning tasks .</p>
        <center><h6>Instructor: Dr. Pavlos Protopapas</h6>
        <img src="/assets/images/people/PavlosProtopapas.jpeg" alt="Pavlos" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#PINNsModal').appendTo('body');
</script>

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
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
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
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#Sql2Modal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="TableauModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Tableau</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>Tableau is a popular visulisation and data analysis tool that helps you create interactive plots and presentations. This workshop will serve as a launching pad to get you started with your very own dashboards.</p>
        <center><!--<h6>Instructor: Kshitij Parwani</h6>
        <img src="/assets/images/people/KshitijParwani.png" alt="Rahul" style="height:200px;margin-right:15px;">--><br><br>
        <h6>Timings</h6>
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#TableauModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="ThreeDCNNsModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">3D CNNs</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>Three Dimensional Convolutional Neural Networks can go beyond 2D images and incorporate volumetric information (like CT scans) or even temportal information (such as event detection in Videos). Features can be extracted from both spatial and temporal dimensions using 3D convolutions.</p>
        <center><!--<h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px;">--><br><br>
        <h6>Timings</h6>
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#ThreeDCNNsModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="CVWorkshopModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">CV Workshop</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>To be updated soon.</p>
        <center><!--<h6>Instructor: Yashraj Wani</h6>
        <img src="/assets/images/people/YashrajWani.png" alt="Yashraj" style="height:200px;margin-right:15px;">--><br><br>
        <h6>Timings</h6>
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#CVWorkshopModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="DoubleDescentModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Double Desecent</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>To be updated soon.</p>
        <center><h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#DoubleDescentModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="CNNTransformerModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">CNN-Transformer</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>To be updated soon.</p>
        <center><!--<h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px;">--><br><br>
        <h6>Timings</h6>
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#CNNTransformerModal').appendTo('body');
</script>

<div class="container">
<div class="modal fade modal-margin" id="ContinualLearningModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog ">
    <div class="modal-content" >
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Continual Learning</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">X</span>
        </button>
      </div>
      <div class="modal-body">
        <p>Text here</p>
        <center><h6>Instructor: Dr. Rahul Dave</h6>
        <img src="/assets/images/people/RahulDave.jpeg" alt="Rahul" style="height:200px;margin-right:15px;"><br><br>
        <h6>Timings</h6>
        <p>6:00 - 8:00 PM IST <br>
        (8:30 - 10:30 AM EST)</p> <br>
        <button class="register-button" onclick="location.href=''">Register</button></center>
      </div>
    </div>
  </div>
</div>
</div>
<script>
     $('#ContinualLearningModal').appendTo('body');
</script>