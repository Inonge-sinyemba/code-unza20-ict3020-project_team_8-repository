		<!-- UPLOAD LECTURE -->
<!DOCTYPE html>
<html>
    <head>
      	 <meta charset="utf-8">
	 <title>Course Information</title>
    </head>
   <link rel="stylesheet" type="text/css" href="MAIN.css">
    <body>
        <header>
                <div id="navlist"> 
                        <a href="home.html" target="blank"><b>Home</b></a> 
                        <a href="#"><b>Courses</b></a> 
                        <a href="download_topic.html" target="blank"><b>Lectures</b></a> 
                    <div class="navlist-right"> 
                        <a href="topic_evaluation.html" target="blank"><b>Feedback</b></a> 
                        <a href="Q_A.html" target="blank"><b>Q and A</a>
                        <a href="guide.html" taregt="blank"> User Guide Manuals</a>
                        <!-- seach bar right align -->
        <div class="search"> 
            <form action="#"> 
                <input type="text"
                    placeholder=" Search "
                    name="search"> 
                <button> 
                    <i class="fa fa-search"
                        style="font-size: 18px;"> 
                    </i> 
                </button> 
            </form> 
        </div> 
    </div> 
                         <select id="ops">
                            <option> Log Out</option>
                            <option> Forums</option>
                            <option> Notifications</option>
                            <option> Profile Settings</option>
                            <option> Feedback</option>
                            <option> Courses</option>
                            <option> Lectures</option>
                            <option> Messages</option>
                        </select> 
                    </div> 
                </div> 
        </header>
    	<nav>
    	       <ul>
    	    	<li><a href="Lspf_System.html" target="blank">Upload Lecture</a></li>
                              <br><br>
    	    	<li><a href="View_feedback.html" target="blank">View Feedback</a></li>
                              <br><br>
     		<li><a href="Q_A.html">Schedule Q and A</a></li>
     	      </ul>  
     	</nav>
        <style type="text/css">
            nav{
                background-color: green;
                font-size: 19px;
            }
        </style>
    </body>
</html>
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>Course Information System</title>
	</head>
		<link rel="stylesheet" type="text/css" href="MAIN.css">
	<body>
		<fieldset>
			<legend>File Picker</legend>
			<p class="Picker">
			<br><br>
<form action="" method="get">
	<input class="but"type="file" name="doc">
	<input type="submit" value="submit">
	<input type="reset" name="reset">
</form>
	 </p>
	    </fieldset>
	    <br><br>
	</body>
</html>

			<!-- Q AND A SESSION -->
<!DOCTYPE html>
<html>
         <head>
                  <meta charset="utf-8">
                  <title>Course Information</title>
         </head>
<link rel="stylesheet" type="text/css" href="MAIN.css">
<body>
          <header>
                <div id="navlist"> 
                        <a href="Student's Interface.html" target="blank"><b>Home</b></a> 
                        <a href="#"><b>Courses</b></a> 
                        <a href="download_topic.html" target="blank"><b>Lectures</b></a> 
                <div class="navlist-right"> 
                        <a href="topic_evaluation.html" target="blank"><b>Feedback</b></a> 
                        <a href="Q_A.html"><b>Q and A</a>
                        <a href="#"><b> User Guide Manuals</a>
<!-- seach bar right align -->
        	<div class="search"> 
            	<form action="#"> 
                	<input type="text"
                    		placeholder=" Search "
                    		name="search"> 
                <button> 
                    	<i class="fa fa-search"
                        style="font-size: 18px;"> 
                    </i> 
                </button> 
            </form> 
        </div> 
    </div>     
            <fieldset class="download-set">
                	<p> Comments:</p>
                	<form class="com" method="post" action="View_feedback.html">
                    	<textarea id="cont" name="Comment" rows="15" cols="179">
                   	</textarea>
</form>
            <button type="submit"> Submit </button>
<style type="text/css">
                    p{
                        text-align: center;
                        background-color: white;
                        padding: 2.5px;
                        margin-top: 3px;
                        margin-left: 9px;
                    }   
                    .com{
                        padding-left: 8px;
                    }
                    #cont{
                        padding: 10px;
                        line-height: 20px;
                    }
                    button{
                        margin-left: 8px;
                        background-color: green;
                    }
</style>
            </fieldset>
     </body>
</html>


		<!-- VIEW FEEDBACK -->
<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<title>Feedback Information</title>
</head>
<link rel="stylesheet" type="text/css" href="MAIN.css">
<body>
	<header>
				<div id="navlist"> 
        				<a href="home.html" target="blank"><b>Home</b></a> 
        				<a href="#"><b>Courses</b></a> 
        				<a href="download_topic.html" target="blank"><b>Lectures</b></a> 
        			<div class="navlist-right"> 
        				<a href="topic_evaluation.html" target="blank"><b>Feedback</b></a> 
        				<a href="Q_A.html"><b>Q and A</a>
        				<a href="guide.html" target="blank"> User Guide Manuals</a>
        				<!-- seach bar right align -->
        <div class="search"> 
            <form action="#"> 
                <input type="text"
                    placeholder=" Search "
                    name="search"> 
                <button> 
                    <i class="fa fa-search"
                        style="font-size: 18px;"> 
                    </i> 
                </button> 
            </form> 
        </div> 
    </div> 
        				 <select id="ops">
        					<option> Log Out</option>
        					<option> Forums</option>
        					<option> Notifications</option>
        					<option> Profile Settings</option>
        					<option> Feedback</option>
        					<option> Courses</option>
        					<option> Lectures</option>
        					<option> Messages</option>
        				</select> 
        			</div> 
    		</div> 
	</header>
<nav>
            <ul>
                <li><a href="Lspf_System.html" target="blank">Upload Lecture</a></li>
                <br><br>
                <li><a href="View_feedback.html" target="blank">View Feedback</a></li>
                <br><br>
                <li><a href="Q_A.html">Schedule Q and A</a></li>
            </ul>  
        </nav>
        <style type="text/css">
            nav{
                background-color: green;
                font-size: 19px;
                background: linear-gradient(to right, green, );
            }
        </style>
<section>
        <p class="see">2019010463@student.unza.zm <a href=""> ||| UNDERSTOOD</a><br><br>
           2019030465@student.unza.zm <a href=""> ||| UNCLEAR</a><br><br>
           2019010479@student.unza.zm <a href=""> ||| UNCLEAR</a><br><br>
           2019010484@student.unza.zm <a href=""> ||| UNDERSTOOD</a><br><br>
           2019010452@student.unza.zm <a href=""> ||| UNDERSTOOD</a><br><br>
           2019010480@student.unza.zm <a href=""> ||| UNCLEAR</a><br><br>
           2019010432@student.unza.zm <a href=""> ||| UNDERSTOOD</a>
        </p>
		</section>
	</body>
</html>


		/* CSS - STYLING THE WHOLE BODY */
body{
	background-color: rgb(234, 236, 253);
	padding:2%;		
	line-height: 25px; /* Space between sentences*/
	margin: 2%;
}


		/* STYLING THE LINKS */
a{
	color: black;
	text-decoration: none;
}
a:hover{
	color: red;
	text-decoration: none;
}
a:active{
	color: red;
	text-decoration: none;
}
a:visited{
	color: black;
	text-decoration: none;
}

		/*stying the navigation */
nav{
	font-weight: bold;
	background: linear-gradient(to right, #2edfff, blue, #2edfff);
	width: 18%;
	height:60%;
	border:4px inset;
}


li {
	font-size: bigger;
	list-style-type:none;
}

section{
	padding:10px;
	text-align:justify;
}

footer{ 
	border-top:1px inset;
	text-align: center;
}


		/* POSITIONING OF THE WEB CONTENT */
nav, section, footer{
	position: absolute;
}

nav, section{
	top: 25%;
	margin-top: 1px;
}

section{
	left:240px;
	right: 25px;
}

footer{
	top:681px;
	left:240px;
	right: 25px;
}


		/* STYLING THE SUBMISSION PAGES*/
.Picker{
	margin: 0.5%;
	width: 98.5%;
	height: 30px;
    border-style: inset;
	background: radial-gradient(#2edfff, blue, #2edfff);
	text-align: center;
	color: white;
}

.but{
	font-family: times new roman;
}

#instruction{
	height: 199px;
	background-image: url(banner1.png);
	background-repeat: repeat-x;
	border: inset 2px;
}

#buttons2{
	margin-top: 2%;
	font-size: 20px;
	text-align: center;
}


		<!-- STUDENT’S INTERFACE -->
<!DOCTYPE html>
<html>
	 <head>
	        <meta charset="utf-8">
	        <title>Course Information</title>
     </head>
	<link rel="stylesheet" type="text/css" href="MAIN.css">
    <body>
		<header>
				<div id="navlist"> 
        				<a href="home.html" target="blank"><b>Home</b></a> 
        				<a href="#"><b>Courses</b></a> 
        				<a href="download_topic.html" target="blank"><b>Lectures</b></a> 
        			<div class="navlist-right"> 
        				<a href="topic_evaluation.html" target="blank"><b>Feedback</b></a> 
        				<a href="Q_A.html"><b>Q and A</a>
        				<a href="guide.html" target="blank"> User Guide Manuals</a>
        			<!-- seach bar right align -->
        <div class="search"> 
            <form action="#"> 
                <input type="text"
                    placeholder=" Search "
                    name="search"> 
                <button> 
                    <i class="fa fa-search"
                        style="font-size: 18px;"> 
                    </i> 
                </button> 
            </form> 
        </div> 
    </div> 
<select id="ops">
        	<option> Log Out</option>
        	<option> Forums</option>
           <option> Notifications</option>
        					<option> Profile Settings</option>
        					<option> Feedback</option>
        					<option> Courses</option>
        					<option> Lectures</option>
        					<option> Messages</option>
        				</select> 
        			      </div> 
    			</div> 
		</header>
		<nav>
			  <p class="nav_head"> Useful Links</p>
			  		<br>
					<a href="download_topic.html" target="blank"> Download Lecture</a>
					<br><br>
					<a href="topic_evaluation.html" target="blank"> Give Feedback </a>
			    	<br><br>
			<a href="Q_A.html" target="blank"> Q and A Session </a>
		<br><br>
	</nav>
    <footer>
        <p>The University of Zambia <br> E-Learning Portal</p>
        <a id="ref1" href="https://www.unza.zm">(https//:www.unza.zm)</a>
    </footer>
	</body>
</html>


		<!-- DOWNLOAD LECTURE -->
<!DOCTYPE html>
<html>
	 <head>
	        <meta charset="utf-8">
	        <title>Course Information</title>
     </head>
	<link rel="stylesheet" type="text/css" href="MAIN.css">
    <body>
	<header>
		<div id="navlist"> 
        			<a href="Student's Interface.html" target="blank"><b>Home</b></a> 
        			<a href="#"><b>Courses</b></a> 
        			<a href="download_topic.html" target="blank"><b>Lectures</b></a> 
        		<div class="navlist-right"> 
        				<a href="topic_evaluation.html" target="blank"><b>Feedback</b></a> 
        				<a href="Q_A.html" target="blank"><b>Q and A</a>
        				<a href="guide.html" target="blank"><b> User Guide Manuals</a>	
<!-- seach bar right align -->
        <div class="search"> 
            	<form action="#"> 
                	<input type="text"
                    	placeholder=" Search "
                    	name="search"> 
                <button> 
                    <i class="fa fa-search"
                        style="font-size: 18px;"> 
                    </i> 
                </button> 
            </form> 
        </div> 
    </div> 		
<fieldset class="download-set">
                <p> Click on any Topic/Link to Download Topic</p>
<style type="text/css">
                    p{
                        text-align: center;
                        background-color: white;
                        padding: 2.5px;
                        margin-top: 3px;
                        margin-left: 9px;
                    }
</style>
                <p id="style2">
                     <a href="#"> EXAMPLE ICT 1110: Number Systems and Representation</a>
                     		<br><br>
                     <a href="#"> EXAMPLE ICT 1110: Peripheral Devices and I/O Subsystem</a>
                     		<br><br>
                     <a href="#"> EXAMPLE ICT 1110: Operating System Functions and Services</a>
                     		<br><br>
                     <a href="#"> EXAMPLE ICT 1110: CPU Instruction Execution</a>
                     		<br><br>
                     <a href="#"> EXAMPLE ICT 1110: Primary Memory</a>
                    		 <br><br>
                     <a href="#"> EXAMPLE ICT 1110: Secondary Storage</a>
                     		<br><br>
                     <a href="#"> EXAMPLE ICT 1110: Instruction Set Architecture III</a>
                     	<br><br>
           </p>
</fieldset>

    <!--<footer>
        			<p>The University of Zambia <br> E-Learning Portal</p>
        			<a id="ref1" href="https://www.unza.zm">(https//:www.unza.zm)</a>
    		</footer>-->
	</body>
</html>


		<!-- TOPIC EVALUATION -->
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Feed Back</title>
</head>
<!-- WE ARE NOW SETTING THE BODY OF THE WEBPAGE -->
<body>
	<link rel="stylesheet" type="text/css" href="MAIN.css">
	<fieldset>
		<p id="instruction"></p>
		<form id="rate" action="confirm-feed-sub.html" method="post">
<p1><b> <a href=""> Example Topic1:</a> </b> <input type="radio" name="rate" value="Unclear"> Vague
<input type="radio" name="rate" value="Understood"> Understood </p1>
   <br><br>
      <br><br>
<!-- PROVIDE CONTROL BUTTONS FOR SUBMISSION & RESET-->
				<p id="buttons"> 
					<input type="submit" value="Submit Feedback">
					<input type="reset" value="Cancel">
				</p>
		</form>
	      </fieldset>
	<footer>
        <p>The University of Zambia <br> E-Learning Portal</p>
        <a id="ref1" href="https://www.unza.zm">(https//:www.unza.zm)</a>
		</footer>
	</body>
</html>

<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>Feed Back</title>
	</head>
<body>
	<link rel="stylesheet" type="text/css" href="MAIN.css">
<fieldset>
	<form id="rate" action="logout.html" method="post">	
<!-- PROVIDE CONTROL BUTTONS FOR CONFIRMATION OF FEEDBACK SUBMISSION -->
		<p id="instruction">
			<p id="buttons2"> 
			Are sure you want to submit feedback?
			<br><br>
			<input type="submit" value="Submit">
			<input type="reset" value="Cancel">
		</p>
	</form>
</fieldset>
		<footer>
        			<p>The University of Zambia <br> E-Learning Portal</p>
        			<a id="ref1" href="https://www.unza.zm">(https//:www.unza.zm)</a>
		</footer>
	</body>
</html>


		<-- Q – A SESSION -->
<!DOCTYPE html>
<html>
     <head>
            <meta charset="utf-8">
            <title>Course Information</title>
     </head>
    <link rel="stylesheet" type="text/css" href="MAIN.css">
    <body>
        <header> 
                <div id="navlist"> 
                        <a href="Student's Interface.html" target="blank"><b>Home</b></a> 
                        <a href="#"><b>Courses</b></a> 
                        <a href="download_topic.html" target="blank"><b>Lectures</b></a> 
                    <div class="navlist-right"> 
                        <a href="topic_evaluation.html" target="blank"><b>Feedback</b></a> 
                        <a href="Q_A.html" target="blank"><b>Q and A</a>
                        <a href="#"><b> User Guide Manuals</a>
<!-- seach bar right align -->
        <div class="search"> 
            <form action="#"> 
                <input type="text"
                    placeholder=" Search "
                    name="search"> 
                <button> 
                    <i class="fa fa-search"
                        style="font-size: 18px;"> 
                    </i> 
                </button> 
            </form> 
        </div> 
    </div> 
            <fieldset class="download-set">
                <p> Comments:</p>
                <form class="com" method="get" action="View_feedback.html">
                    <textarea id="cont" name="Comment" rows="15" cols="179">
                    </textarea>
       </form>
            <button type="submit"> Submit </button>
                <style type="text/css">
                    p{
                        text-align: center;
                        background-color: white;
                        padding: 2.5px;
                        margin-top: 3px;
                        margin-left: 9px;
                    }
                    .com{
                        padding-left: 8px;
                    }
                    #cont{
                        padding: 10px;
                        line-height: 20px;
                    }
                    button{
                        margin-left: 8px;
                        background-color: green;
                    }
                </style>
            </fieldset>
    </body>
</html>


		<!-- GUIDE MANUALS -->
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>Manuals & Guidance</title>
	</head>
<link rel="stylesheet" type="text/css" href="MAIN.css">
<body>
	<header>
		<div id="navlist"> 
        		<a href="home.html" target="blank"><b>Home</b></a> 
        		<a href="#"><b>Courses</b></a> 
        		<a href="download_topic.html" target="blank"><b>Lectures</b></a> 
<div class="navlist-right"> 
        	<a href="topic_evaluation.html" target="blank"><b>Feedback</b></a> 
        		<a href="Q_A.html" target="blank"><b>Q and A</a>
        		<a href="guide.html" target="blank"><b> User Guide Manuals</b></a>
        				<!-- seach bar right align -->
        <div class="search"> 
            <form action="#"> 
                <input type="text"
                    placeholder=" Search "
                    name="search"> 
               <button> 
                    <i class="fa fa-search"
                        style="font-size: 18px;"> 
                    </i> 
                </button> 
            </form> 
        </div> 
    </div> 
        			</div> 
    			</div> 

		</header>
<nav>
	  <p class="nav_head"> Useful Links</p>
		<br>
			<a href="download_topic.html" target="blank"> Download Lecture</a>
			<br><br>
			<a href="topic_evaluation.html" target="blank"> Give Feedback </a>
			<br><br>
			<a href="Q_A.html" target="blank"> Q and A Session </a>
			<br><br>
</nav>
<section>
	<h4>DOWNLOADING LECTURES</h4>
	<P>
		<ol>
			<li>Click on the <a id="linkit" href="download_topic.html"> Download Lecture</a></u> link in the <em>Navigation Pane</em> or <em>Header</em>.</li>
			<li>A window with a list of Topics will be displayed.</li>
			<li>Click on any Topic and will be automatically downloaded.</li>
		</ol>
	</P>
	<h4>RATING TOPICS</h4>
		<p> 
			<ol>
				<li>Click on the <a id="linkit" href=""> Give Feedback</a> link in the <em> Navigation Pane</em> or <em>Header</em>.</li>
				<li>A window with a list of Topics next to Radio Buttons will be displayed.</li>
				<li>For each Topic, click on any toggle between the <em>YES</em> and <em>NO</em> button to pick the answer that suits your understanding of the topic.</li>
				<li>Click on the <em>Submit</em> button at the bottom.</li>
				<li>A new Screen will be displayed, requesting for confirmation.</li>
				<li>Click on <em>Submit</em> to confirm, and <em>Cancel</em> to return to the previous page</li>
				<li>Upon clicking the Submit button, a New Screen will appear requesting you to <em>Log Out</em> or to go <em>Back</em> to the Home page.</li>
			</ol>
		</p>

	<h4>Q AND A SESSION</h4>
		<p> 
			<ol>
				<li>Click on the <a id="linkit" href="Q_A.html">Q and A Session</a> in the <em>Navigation Pane</em> or in the Header <a id="linkit" href="Q_A.html">Q and A</a>.</li>
				<li>A New Screen will be displayed.</li>
			</ol>
		</p>
</section>
 <footer>
        <p>The University of Zambia <br> E-Learning Portal</p>
        <a id="ref1" href="https://www.unza.zm">(https//:www.unza.zm)</a>
    </footer>
<style type="text/css">
	#linkit{
		color: blue;
		text-decoration: underline;
	}
	h4{
		color: navy;
		text-align: left;
	}
		</style>
	</body>
</html>
LOG OUT 

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Course Info</title>
</head>
	<!-- WE ARE NOW SETTING THE BODY OF THE WEBPAGE -->
<body>
	<link rel="stylesheet" type="text/css" href="MAIN.css">
		<fieldset>
			<p id="instruction"></p>
			<form id="rate" action="Student's Interface.html" method="post">		
<!-- PROVIDE CONTROL BUTTONS FOR CONFIRMATION OF FEEDBACK SUBMISSION -->
		<p id="buttons2"> 
			<input type="submit" value="Back">
			<input type="button" value="Logout">
		</p>
	</form>
</fieldset>
    <footer>
        <p>The University of Zambia <br> E-Learning Portal</p>
        <a id="ref1" href="https://www.unza.zm">(https//:www.unza.zm)</a>
    		</footer>
	</body>
</html>

