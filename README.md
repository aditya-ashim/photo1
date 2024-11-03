<!DOCTYPE html>
<html>

<head>
  <title>Calcutta Public School > Register Online</title>
  <link rel="stylesheet" href="register_online.css">
</head>

<body>

  <!------------Header section Start------------------->

  <div id="fullpage">
    <header>
      <div class="logo"><img src="images/top.jpg" alt="logo"></div>
    </header>
    <!------------Main section Start------------------->

    <div class="parent">
      <div class="div1">
        <nav id="nav">
          <ul class="nav-links">
            <li><a href="index.html">Home</a></li>
            <li><a href="vision.html">Vision</a></li>
            <li><a href="history.html">History</a></li>
            <li><a href="location.html">Location</a></li>
            <li><a href="organisation.html">Organisation</a></li>
            <li><a href="curriculum.html">Curriculum</a></li>
            <li><a href="school_uniform.html">School Uniform</a></li>
            <li><a href="teaching_staff.html">Teaching Staff</a></li>
            <li><a href="facilities.html">Facilities</a></li>
            <li><a href="activities.html">Activities</a></li>
            <li><a href="rules.html">Rules</a></li>
            <li><a href="register_online.html">Register online</a></li>
            <li><a href="photogallery.html">Photogallery</a></li>
            <li><a href="contact_us.html">Contact Us</a></li>
            <li><a href="site_map.html">Site Map</a></li>
          </ul>
        </nav>
      </div>
      <div class="div2">
        <p>
          <font><strong class="vision">Register online</font></strong>
        <div class="vision-border"></div>
        </p>
      </div>
      <div class="div3">
        <p class="para1">Instruction to fill in the form :<br><br>

          Fill in the form and click the submit button to mail this page to us. Click the Reset button to clear the
          content of the form.</p>

        <div class="form_container">
          <!-----------------------------------------Student Name------------------------------------------>
          <div class="formgroup">
            <label for="StudentName">Name of the student<br>(Use Block Letters)</label>
            <input type="text" name="StudentName" id="StudentName" oninput="this.value = this.value.toUpperCase()">
          </div>
          <!-----------------------------------------Admission to Class------------------------------------------>
          <div class="formgroup">
            <label for="AdmissionToClass">Admission to Class</label>
            <select name="AdmissionToClass" id="AdmissionToClass">
              <option value="">Choose</option>
              <option value="LowerNursery">Lower Nursery</option>
              <option value="UpperNursery">Upper Nursery</option>
              <option value="Transition">Transition</option>
              <option value="ClassOne">Class l</option>
              <option value="ClassTwo">Class ll</option>
              <option value="ClassThree">Class lll</option>
              <option value="ClassFour">Class lV</option>
              <option value="ClassFive">Class V</option>
              <option value="ClassSix">Class Vl</option>
              <option value="ClassSeven">Class Vll</option>
              <option value="ClassEight">Class Vlll</option>
              <option value="ClassNine">lX</option>
              <option value="ClassElevenArts">Xl-Arts </option>
              <option value="ClassElevenScience">Xl-Science</option>
              <option value="ClassElevenCommerce">Xl-Commerce</option>
            </select>
          </div>

          <!-----------------------------------------Academic year------------------------------------------>

          <div class="formgroup">
            <label for="AcademicYear">For Academic Year</label>
            <strong class="Btag1">March</strong>
            <select name="AcademicYear" id="AcademicYear">
              <option value="">Choose</option>
              <option value="2001">2001</option>
              <option value="2002">2002</option>
              <option value="2003">2003</option>
              <option value="2004">2004</option>
              <option value="2005">2005</option>
              <option value="2006">2006</option>
              <option value="2007">2007</option>
              <option value="2008">2008</option>
              <option value="2009">2009</option>
              <option value="2010">2010</option>
            </select>
          </div>
          <!-----------------------------------------Date of birth------------------------------------------>
          <div class="formgroup ">
            <label for="y_of_birth">Select Date Of Birth</label>
            <b>Year</b>
            <select name="y_of_birth" id="y_of_birth">
              <option value="">Choose</option>
              <option value="1980">1980</option>
              <option value="1981">1981</option>
              <option value="1982">1982</option>
              <option value="1983">1983</option>
              <option value="1984">1984</option>
              <option value="1985">1985</option>
              <option value="1986">1986</option>
              <option value="1987">1987</option>
              <option value="1988">1988</option>
              <option value="1989">1989</option>
              <option value="1990">1990</option>
              <option value="1991">1991</option>
              <option value="1992">1992</option>
              <option value="1993">1993</option>
              <option value="1994">1994</option>
              <option value="1995">1995</option>
              <option value="1996">1996</option>
              <option value="1997">1997</option>
              <option value="1998">1998</option>
              <option value="1999">1999</option>
              <option value="2000">2000</option>
              <option value="2001">2001</option>
              <option value="2002">2002</option>
              <option value="2003">2003</option>
              <option value="2004">2004</option>
              <option value="2005">2005</option>
              <option value="2006">2006</option>
              <option value="2007">2007</option>
              <option value="2008">2008</option>
              <option value="2009">2009</option>
              <option value="2010">2010</option>
            </select>

            <b>Month</b>
            <select name="m_of_birth" id="m_of_birth">
              <option value="">Choose</option>
              <option value="Jan">January</option>
              <option value="Feb">February</option>
              <option value="Mar">March</option>
              <option value="Apr">April</option>
              <option value="May">May</option>
              <option value="Jun">June</option>
              <option value="July">July</option>
              <option value="Aug">August</option>
              <option value="Sep">September</option>
              <option value="Oct">October</option>
              <option value="Nov">November</option>
              <option value="Dec">December</option>
            </select>

            <b>Day</b>
            <select name="d_of_birth" id="d_of_birth">
              <option value="">Choose</option>
              <option value="1">1</option>
              <option value="2">2</option>
              <option value="3">3</option>
              <option value="4">4</option>
              <option value="5">5</option>
              <option value="6">6</option>
              <option value="7">7</option>
              <option value="8">8</option>
              <option value="9">9</option>
              <option value="10">10</option>
              <option value="11">11</option>
              <option value="12">12</option>
              <option value="13">13</option>
              <option value="14">14</option>
              <option value="15">15</option>
              <option value="16">16</option>
              <option value="17">17</option>
              <option value="18">18</option>
              <option value="19">19</option>
              <option value="20">20</option>
              <option value="21">21</option>
              <option value="22">22</option>
              <option value="23">23</option>
              <option value="24">24</option>
              <option value="25">25</option>
              <option value="26">26</option>
              <option value="27">27</option>
              <option value="28">28</option>
              <option value="29">29</option>
              <option value="30">30</option>
              <option value="31">31</option>
            </select>
          
          </div>
          <!-----------------------------------------Place of birth------------------------------------------>
          <div class="formgroup ">
            <label for="PlaceOfBirth">Place Of Birth</label>
            <input type="text" name="PlaceOfBirth" id="PlaceOfBirth" maxlength="50">
          </div>
          <!-----------------------------------------FatherName------------------------------------------>
          <div class="formgroup ">
            <label for="FatherName">Father's Full Name</label>
            <input type="text" name="FatherName" id="FatherName" maxlength="50">
          </div>
          <!-----------------------------------------MotherName------------------------------------------>
          <div class="formgroup ">
            <label for="MotherName">Mother's Full Name</label>
            <input type="text" name="MotherName" id="MotherName" maxlength="50">
          </div>
          <!-----------------------------------------Residence Address------------------------------------------>
          <div class="formgroup ">
            <label for="R_address">Residence Address</label>
            <textarea id="R_address" name="R_address" id="R_address" rows="3"></textarea>
          </div>
          <!-----------------------------------------City------------------------------------------>
          <div class="formgroup ">
            <label for="City">City</label>
            <input type="text" name="City" id="City" maxlength="50">
          </div>
          <!-----------------------------------------State------------------------------------------>
          <div class="formgroup ">
            <label for="State">State</label>
            <input type="text" name="State" id="State" maxlength="50">
          </div>
          <!-----------------------------------------Pincode------------------------------------------>
          <div class="formgroup ">
            <label for="Pincode">Pincode</label>
            <input type="text" name="Pincode" id="Pincode" maxlength="6">
          </div>
          <!-----------------------------------------Phone(R) (With STD Code)------------------------------------------>
          <div class="formgroup ">
            <label for="PhRSTD">Phone(R) (With STD Code)</label>
            <input type="text" name="PhRSTD" id="PhRSTD" maxlength="20">
          </div>
          <!-----------------------------------------E-mail------------------------------------------>
          <div class="formgroup ">
            <label for="email">E-mail</label>
            <input type="text" name="email" id="email" maxlength="150">
          </div>
          <!-----------------------------------------Father's Occupation------------------------------------------>
          <div class="formgroup ">
            <label for="FatherOcc">Father's Occupation</label>
            <input type="text" name="FatherOcc" id="FatherOcc" maxlength="50">
          </div>
          <!-----------------------------------------Office Address------------------------------------------>
          <div class="formgroup ">
            <label for="O_address">Office Address</label>
            <textarea id="O_address" name="O_address" rows="3"></textarea>
          </div>

          <!-----------------------------------------Phone(O) (With STD Code)------------------------------------------>
          <div class="formgroup ">
            <label for="PhOSTD">Phone(O) (With STD Code)</label>
            <input type="text" name="PhOSTD" id="PhOSTD" maxlength="20">
          </div>
          <!-----------------------------------------Local Guardian's Name------------------------------------------>
          <div class="formgroup ">
            <label for="LocalGuardian">Local Guardian's Name</td>
              <input type="text" name="LocalGuardian" id="LocalGuardian" maxlength="50">
          </div>
          <!-----------------------------------------Nationality Of Parents------------------------------------------>
          <div class="formgroup ">
            <label for="nationality">Nationality Of Parents</label>
            <input type="text" name="nationality" id="nationality" maxlength="50">
          </div>
          <!-----------------------------------------Name Of School Last Attended------------------------------------------>
          <div class="formgroup ">
            <label for="lastschool">Name Of School Last<br> Attended</label>
            <input type="text" name="lastschool" id="lastschool" maxlength="150">
          </div>
          <!-----------------------------------------Address Of School Last Attended------------------------------------------>
          <div class="formgroup ">
            <label for="S_address">Address Of School Last<br> Attended</label>
            <textarea name="S_address" id="S_address" rows="3"></textarea>
          </div>
          <!-----------------------------------------Class Studied------------------------------------------>
          <div class="formgroup ">
            <label for="ClassStudied">Class Studied</label>
            <select name="ClassStudied" id="ClassStudied">
              <option value="">Choose</option>
              <option value="LowerNursery">Lower Nursery</option>
              <option value="UpperNursery">Upper Nursery</option>
              <option value="Transition">Transition</option>
              <option value="ClassOne">Class l</option>
              <option value="ClassTwo">Class ll</option>
              <option value="ClassThree">Class lll</option>
              <option value="ClassFour">Class lV</option>
              <option value="ClassFive">Class V</option>
              <option value="ClassSix">Class Vl</option>
              <option value="ClassSeven">Class Vll</option>
              <option value="ClassEight">Class Vlll</option>
              <option value="ClassNine">Class lX</option>
              <option value="ClassTen">Class X</option>
              <option value="ClassElevenArts">Xl-Arts </option>
              <option value="ClassElevenScience">Xl-Science</option>
              <option value="ClassElevenCommerce">Xl-Commerce</option>
            </select>
          </div>
          <!-----------------------------------------Rank In Class------------------------------------------>
          <div class="formgroup ">
            <label for="rank">Rank In Class</label>
            <input type="text" name="rank" id="rank" maxlength="4">
          </div>

          <!-----------------------------------------Payment Section Start------------------------------------------>

          <div class="formgroup ">
            <label>Payment Details</label>
          </div>

          <div class="formgroup ">
            <div class="paymentSection">
              <div class="cash">
                <input type="radio" id="cash" name="payment" value="cash" onclick=" EnableDisableTextBox();">
                <label for="cash">CASH</label>
              </div>
              <div class="cheque">
                <input type="radio" id="cheque" name="payment" value="cheque" onclick=" EnableDisableTextBox();">
                <label for="cheque">CHEQUE</label>
              </div>
              <div class="draft">
                <input type="radio" id="draft" name="payment" value="draft" onclick=" EnableDisableTextBox();">
                <label for="draft">DEMAND DRAFT</label>
              </div>
            </div>
          </div>

          <div class="formgroup">
            <div class="paymentSection1">
              <div class="cash1">
                <label for="cashAmount">AMOUNT</label>
                <input type="text" id="cashAmount" name="cashAmount" disabled>
              </div>
              <div class="cheque1">
                <label for="chequeNo">CHEQUE NO</label>
                <input type="text" id="chequeNo" name="chequeNo" disabled>
                <label for="chequeDate">CHEQUE DATE</label>
                <input type="date" id="chequeDate" name="chequeDate" disabled>
              </div>
              <div class="draft1">
                <label for="draftNo">DD NO</label>
                <input type="text" id="draftNo" name="draftNo" maxlength="6" disabled>
                <label for="draftDate">DD DATE</label>
                <input type="date" id="draftDate" name="draftDate" disabled>
              </div>
            </div>
          </div>

        </div>
      </div>

      <div class="div4">
        <footer class="footer">
          <p>Powered by&nbsp<a href="https://www.google.com" target="_blank" class="afoot">Google.com</a></p>
        </footer>
      </div>
    </div>


  </div>
</body>

</html>



* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html, body {
    font-family: Verdana, sans-serif;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    overflow-x: hidden;
overflow-y:scroll;
}

body {
    overflow: hidden;
}

.logo img {
    width: 780px;
    height: 108px;
}

#fullpage {
    background: url('images/bg_watermark.jpg') repeat-y;
    width: 780px;
}

img{
display:block;
width:100%;
}

a {
    text-decoration: none;
    color: #f8cf44;
    font-size: 10px;
    font-weight: 700;
    transition: color 0.3s ease;
}

a:hover {
    color: #fff;
}

.afoot {
    color: #000;
}

.afoot:hover {
    color: red;
}

.vision {
    position: absolute;
    width: 100%;
    height: 34px;
    color: #FFD700;
    padding: 12px 10px 0;
    font-weight: 900;
    letter-spacing: 1.6px;
    font-size: 13.9px;
    overflow: hidden;
margin-top:-2px;
}

.vision-border {
    margin-top:29.2px;
margin-left: -10px;
display: inline-block;
background: rgb(7,13,86);
background: linear-gradient(131deg, rgba(7,13,86,1) 1%, rgba(45,68,136,1) 8%, rgba(46,60,135,1) 90%, rgba(7,13,86,1) 94%);
height:1px;
padding-left:210px;
}

p,label {
    font-size: 13px;
    color: #fff;
    line-height: 20px;
    word-spacing: 1px;
}

ul {
    margin-top: -3px;
}

ul li {
    list-style-type: none;
}

#nav {
    background: url('images/extra.jpg') repeat-y;
    min-width: 159px;
    height: 100%;
    padding: 14px 14.2px;
}

.nav-links {
    position: sticky;
}

.form_container {
    display: flex;
flex-direction:column;
    align-items: center;
justify-content:flex-start;
gap:7px;

}

.formgroup{
width:97%;
display: flex;
justify-content:flex-start;
align-items: center;
gap:65px;
}



#StudentName{
width:350px;
}

#AdmissionToClass{
margin-left:13px;
width:118px;
}

#AcademicYear{
position:relative;
right:30px;
width:70px;
}

.Btag1{
font-size:13px;
color:#fff;
font-weight:900;
margin-left:15px;
}
.Btag4{
font-size:13px;
color:#fff;
font-weight:900;
margin-left:26px;
}
.text{
display:flex;
justify-content:center;
align-items:center;
position:absolute;
color:#fff;
gap:79px;
left:660px;
}

#y_of_birth{
position:relative;
left:42px;
width:70px;
}
#m_of_birth{
position:relative;
left:55px;
width:90px;
}
#d_of_birth{
position:relative;
left:50px;
width:70px;
}
#PlaceOfBirth{
position:relative;
left:48px;
width:300px;
}
#FatherName{
position:relative;
left:16px;
width:300px;
}
#MotherName{
position:relative;
left:12px;
width:300px;
}

#R_address{
width:200px;
position:relative;
left:17px;
}

#City{
width:250px;
position:relative;
left:114px;
}

#State{
width:250px;
position:relative;
left:105px;
}

#Pincode{
width:250px;
position:relative;
left:89px;
}

#PhRSTD{
width:250px;
position:relative;
right:39.5px;
}
#email{
width:250px;
position:relative;
left:98px;
}


#FatherOcc{
width:250px;
position:relative;
left:10px;
}
#O_address{
width:200px;
position:relative;
left:45px;
}
#PhOSTD{
width:250px;
position:relative;
right:40px;
}
#LocalGuardian{
width:250px;
position:relative;
left:27.5px;
}
#nationality{
width:250px;
position:relative;
left:-5px;
}

#lastschool{
width:250px;
position:relative;
left:0px;
}

#S_address{
width:200px;
position:relative;
right:13px;
}

#ClassStudied{
position:relative;
left:51px;
width:118px;
}

#rank{
width:250px;
position:relative;
left:49px;
}



.paymentSection{
display:flex;
justify-content:center;
align-items:center;
justify-content:center;
gap:140px;
}
.paymentSection1 input{
    width: 90px;
}

.paymentSection1{
display:flex;
justify-content:center;
align-items:center;
justify-content:center;
gap:40px;
}

.strong {
    color: #f8cf44;
    font-weight: 800;
    font-size: 20px;
}

.footer {
    background: url('images/bottom_img.jpg') no-repeat;
    width: 780px;
    height: 27px;
}

.footer p {
    color: #000;
    font-weight: 900;
    font-size: 10px;
    padding: 3.5px 12px;
    display: flex;
    align-items: center;
}

.para1, .para2, .para3 {
    padding-bottom: 17px;
    font-size: 13px;
}



.parent {
    display: grid;
    grid-template-columns: 169px 1fr;
    grid-template-rows: auto;
    gap: 0;
}

.div1 {
    grid-column: 1 / 2;
    grid-row: 1 / span 5;
}

.div2 {
    grid-column: 2 / 3;
    grid-row: 1 / 2;
    height: 40px;
}

.div3 {
    padding: 10px;
margin-right:15px;
    grid-column: 2 / 3;
    grid-row: 2 / span 3;
}

.div4 {
    margin-top: -5px;
    grid-column: 1 / -1;
    grid-row: 6 / 7;
}



<!DOCTYPE html>
<html>
  <head>
    <title>Calcutta Public School > Photogallery</title>
<link rel="stylesheet" href="photogallery.css">
  </head>
  <body>

<!------------Header section Start------------------->

<div id="fullpage">
<header>
<div class="ANNUAL FUNCTION"><img src="images/top.jpg" alt="ANNUAL FUNCTION"></div>
</header>
<!------------Main section Start------------------->

<div class="parent">
    <div class="div1"><nav id="nav" >
 <ul class="nav-links">
                                            <li><a href="index.html">Home</a></li>
                                            <li><a href="vision.html">Vision</a></li>
                                            <li><a href="history.html">History</a></li>
                                            <li><a href="location.html">Location</a></li>
                                            <li><a href="organisation.html">Organisation</a></li>
                                            <li><a href="curriculum.html">Curriculum</a></li>
                                            <li><a href="school_uniform.html">School Uniform</a></li>
                                            <li><a href="teaching_staff.html">Teaching Staff</a></li>
                                            <li><a href="facilities.html">Facilities</a></li>
                                            <li><a href="activities.html">Activities</a></li>
                                            <li><a href="rules.html">Rules</a></li>
                                            <li><a href="register_online.html">Register online</a></li>
                                            <li><a href="photogallery.html">Photogallery</a></li>
                                            <li><a href="contact_us.html">Contact Us</a></li>
                                            <li><a href="site_map.html">Site Map</a></li>
</ul>
</nav>
</div>
    <div class="div2"><p><font><strong class="vision">Photogallery</font></strong><div class="vision-border"></div></p>
</div>
    <div class="div3">
<p class="txtContainer">
<b>ANNUAL FUNCTION</b>
</p>

<p class="imgContainer">
<img src="images/stage.gif" alt="ANNUAL FUNCTION" class="facImg image-popup">
<img src="images/drama_4.gif" alt="ANNUAL FUNCTION" class="facImg image-popup">
</p><br>
<p class="imgContainer">
<img src="images/drama_3.gif" alt="ANNUAL FUNCTION" class="facImg image-popup">
<img src="images/dance.gif" alt="ANNUAL FUNCTION" class="facImg image-popup">
</p><br>
<p class="imgContainer1">
<img src="images/drama2.gif" alt="ANNUAL FUNCTION" class="facImg d2 image-popup">
<img src="images/boy.gif" alt="ANNUAL FUNCTION" class="boy image-popup">
</p>
<p class="txtContainer">
<b>LABS</b>
</p>

<p class="imgContainer">
<img src="images/lab_3.gif" alt="BIOLOGY LAB" class="facImg image-popup">
<img src="images/lab_6.gif" alt="PHYSICS LAB" class="facImg image-popup">
</p>
<p class="txtContainer">
<b>BIOLOGY LAB</b>
<b>PHYSICS LAB</b>
</p>
<p class="txtContainer">
<b>RECTOR</b>
</p>
<p class="imgContainer">
<img src="images/pricipal.gif" alt="RECTOR" class="facImg image-popup">
</p>

</div>
    <div class="div4"><footer class="footer">
<p>Powered by&nbsp<a href="https://www.google.com" target="_blank" class="afoot">Google.com</a></p>
</footer></div>
</div>
</div>

 <!-------------------------------------------------- Modal Structure Start ------------------------------------------>

<section>
    <div id="myModal" class="modal-div">
                <span class="close" title="Close">&times;</span>
                <div class="modal-content">
<img id="modalImg" src=""></div>
                <div class="caption-container" style="width: 100%; text-align: center;">
<p id="caption"></p>
                </div>
                <a class="prev" title="Previous">&#10094;</a>
                <a class="next" title="Next">&#10095;</a>
           
    </div>
</section>



<script src="photogallery.js"></script>
  </body>
</html>




* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html, body {
    font-family: Verdana, sans-serif;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    overflow-x: hidden;
overflow-y:scroll;
}

body {
    overflow: hidden;
}

.logo img {
    width: 780px;
    height: 108px;
}

#fullpage {
    background: url('images/bg_watermark.jpg') repeat-y;
    width: 780px;
}

img{
display:block;
width:100%;
}

a {
    text-decoration: none;
    color: #f8cf44;
    font-size: 10px;
    font-weight: 700;
    transition: color 0.3s ease;
}

a:hover {
    color: #fff;
}

.afoot {
    color: #000;
}

.afoot:hover {
    color: red;
}

.vision {
    position: absolute;
    width: 100%;
    height: 34px;
    color: #FFD700;
    padding: 12px 10px 0;
    font-weight: 900;
    letter-spacing: 1.6px;
    font-size: 13.9px;
    overflow: hidden;
margin-top:-2px;
}

.vision-border {
    margin-top:29.2px;
margin-left: -10px;
display: inline-block;
background: rgb(7,13,86);
background: linear-gradient(131deg, rgba(7,13,86,1) 1%, rgba(45,68,136,1) 8%, rgba(46,60,135,1) 90%, rgba(7,13,86,1) 94%);
height:1px;
padding-left:210px;
}

p {
    font-size: 13px;
    color: #fff;
    line-height: 20px;
    word-spacing: 1px;
}

ul {
    margin-top: -3px;
}

ul li {
    list-style-type: none;
}

#nav {
    background: url('images/extra.jpg') repeat-y;
    min-width: 159px;
    height: 100%;
    padding: 14px 14.2px;
}

.nav-links {
    position: sticky;
}

.main {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
}

.strong {
    color: #f8cf44;
    font-weight: 800;
    font-size: 20px;
}

.footer {
    background: url('images/bottom_img.jpg') no-repeat;
    width: 780px;
    height: 27px;
}

.footer p {
    color: #000;
    font-weight: 900;
    font-size: 10px;
    padding: 5px 12px;
    display: flex;
    align-items: center;
}

.para1, .para2{
    padding-bottom: 17px;
    font-size: 13px;
}
.para3{
padding-top:17px;
padding-bottom: 17px;
}
.para4{
padding-bottom: 17px;
}
.para4:last-child{
padding-bottom: 25px;
}

.image-popup{
transition: transform .2s ease-in-out;
}
.image-popup:hover{
cursor:pointer;
transform: scale(1.1);
}

.imgContainer, .txtContainer{
display:flex;
justify-content:center;
align-items:center;
gap:30px;
}


.txtContainer b{
text-align:center;
width: 250px;
padding-top:5px;
margin-bottom:20px;
}
.facImg {
    width: 250px;
    height: 164px;
}

.boy{
width: 164px;
    height: 250px;
margin-right:30px;
}

.imgContainer1{
display:flex;
justify-content:space-evenly;
align-items:center;
}

.d2{
margin-right:60px;
}

.imgContainer:last-child{
margin-bottom:30px;
}


.parent {
    display: grid;
    grid-template-columns: 169px 1fr;
    grid-template-rows: auto;
    gap: 0;
}

.div1 {
    grid-column: 1 / 2;
    grid-row: 1 / span 5;
}

.div2 {
    grid-column: 2 / 3;
    grid-row: 1 / 2;
    height: 40px;
}

.div3 {
    padding: 10px;
margin-right:15px;
    grid-column: 2 / 3;
    grid-row: 2 / span 3;
}

.div4 {
    margin-top: -5px;
    grid-column: 1 / -1;
    grid-row: 6 / 7;
}















/*-----------------------------------------Modal CSS Start---------------------------------------- */



.modal-div {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 50%;
    top: 60.4%;
transform:translate(-50%,-50%);
    width: 780px;
    height: 450px;
max-width:90%;
max-height:90%;
    background-color: gray ;
    table-layout: fixed;
border:1px solid #949494;
}





/* Media query for higher zoom level */
        @media (resolution: 120dpi) {
            .modal-div {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 50%;
    top: 75.6%;
transform:translate(-50%,-50%);
    width: 780px;
    height: 450px;
max-width:90%;
max-height:90%;
    background-color: gray ;
    table-layout: fixed;
border:1px solid #949494;
}
        }


.modal-content {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%; 

}

.modal-content img {
margin-left: auto;
  margin-right: auto;
object-fit:contain;
display:block;
  width: 515px;
  height: 338px;
    margin-bottom: 30px;
border-radius:5px;
}


.caption-container {
    width: 100%;
    text-align: center;
position:relative;
bottom:25px;
}
.caption-container p {
color:#000;
font-size:14px;
font-weight:900;
    text-align: center; 
    font-size: 16px; 
    margin-top: -15px; 
    margin-bottom: 30px;
}

.prev, .next {
    position: absolute;
    top: 40%;
    padding: 16px;
position:fixed;
    color: white;
    font-size: 20px;
    font-weight: bold;
    cursor: pointer;
    background-color:rgba(0, 0, 0, 0.4);
transition:all 0.2s ease-in-out;
-webkit-user-select: none; 
    -moz-user-select: none;
}
.prev:hover, .next:hover {
background-color: rgba(0, 0, 0, 0.7);
color:#fff;
border-radius:50%;
margin:0px 0.5px;
}

.prev {
    left: 0;
}

.next {
    right: 0;
}

.close {
    position: absolute;
    top: 5px;
    right: 10px;
    color: white;
    font-size: 30px;
    font-weight: bold;
    cursor: pointer;
    transition: color 0.3s ease-in-out;
}

.close:hover{
color: #000;

}
.modal-content img.boy-gif {
width:246px;
height:375px;
margin-left: auto;
  margin-right: auto;
display:block;
}


.image-popup{
-webkit-user-select: none; 
    -moz-user-select: none;
filter:contrast(115%);
}
.image-popup:hover{
cursor:pointer;
filter:contrast(100%);
}
.special{ 
width:246px;
height:375px;
}

 /* Modal CSS for Firefox */

@-moz-document url-prefix() {
.modal-div {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 50%;
    top: 60.4%;
transform:translate(-50%,-50%);
    width: 780px;
    height: 450px;
max-width:90%;
max-height:90%;
    background-color: gray ;
    table-layout: fixed;
border:1px solid #949494;
}

.modal-content {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%; 
}

.modal-content img {
margin-left: auto;
  margin-right: auto;
object-fit:contain;
display:block;
  width: 515px;
  height: 338px;
    margin-top: 30px;
border-radius:5px;
}


.caption-container {
    width: 100%;
    text-align: center;
position:relative;
bottom:25px;
}
.caption-container p {
color:#000;
font-size:14px;
font-weight:900;
    text-align: center; 
    font-size: 16px; 
    margin-top: -15px; 
    margin-bottom: 0px;
}

#caption{
margin-top:50px;

}

.modal-content img.boy-gif {
width:245px;
height:375px;
margin-bottom:-8px;
margin-left: auto;
  margin-right: auto;
display:block;
}

.prev, .next {
    position: absolute;
    top: 40%;
    padding: 15.5px;
position:fixed;
    color: white;
    font-size: 20px;
    font-weight: bold;
    cursor: pointer;
    background-color:rgba(0, 0, 0, 0.4);
transition:all 0.2s ease-in-out;
-webkit-user-select: none; 
    -moz-user-select: none;
}
.prev:hover, .next:hover {
background-color: rgba(0, 0, 0, 0.7);
color:#fff;
border-radius:50%;
margin:0px 0.5px;
}

.prev {
    left: 0;
}

.next {
    right: 0;
}

}









const modal = document.getElementById("myModal");
const modalImg = document.getElementById("modalImg");
const captionText = document.getElementById("caption");
const closeModal = document.getElementsByClassName("close")[0];
const images = document.querySelectorAll(".image-popup");

let currentIndex = 0;

images.forEach((img, index) => {
    img.addEventListener("click", function () {
        currentIndex = index; 
        showModal();
    });
});

closeModal.addEventListener("click", function () {
    modal.style.display = "none";
});

function showModal() {
    modal.style.display = "table";
    modalImg.src = images[currentIndex].src;
    captionText.innerHTML = images[currentIndex].alt;

    // Set specific class for boy.gif


    if (images[currentIndex].src.includes('boy.gif')) {
        modalImg.classList.add('boy-gif'); 
    } else {
        modalImg.classList.remove('boy-gif'); 
    }
toggleButtons();
}

function updateModal() {
    modalImg.src = images[currentIndex].src;
    captionText.innerHTML = images[currentIndex].alt;

    // Set specific class for boy.gif
    if (images[currentIndex].src.includes('boy.gif')) {
        modalImg.classList.add('boy-gif'); 
    } else {
        modalImg.classList.remove('boy-gif'); 
    }
toggleButtons();
}

document.addEventListener("keydown", function (event) {
    if (event.key === "Escape") {
        modal.style.display = "none"; 
    }
});

/*window.addEventListener('keydown', event => {
  if (event.key == "ArrowLeft") {
    currentIndex = (currentIndex === 0) ? images.length - 1 : currentIndex - 1;
    updateModal();

  }else if (event.key == "ArrowRight") {
   currentIndex = (currentIndex === images.length - 1) ? 0 : currentIndex + 1;
    updateModal();
  }
}); */

// Next and Previous functionality
document.querySelector(".prev").addEventListener("click", function () {
    currentIndex = (currentIndex === 0) ? images.length - 1 : currentIndex - 1;
    updateModal();
});

document.querySelector(".next").addEventListener("click", function () {
    currentIndex = (currentIndex === images.length - 1) ? 0 : currentIndex + 1;
    updateModal();
});

function toggleButtons(){

//document.querySelector(".prev").style.display="inline-block";
//document.querySelector(".next").style.display="inline-block";

if(currentIndex===0){
document.querySelector(".prev").style.display="none";	
}else{
document.querySelector(".prev").style.display="inline-block";
}

if(currentIndex===images.length - 1){
document.querySelector(".next").style.display="none";
}else{
document.querySelector(".next").style.display="inline-block";
}
}


<!DOCTYPE html>
<html>
  <head>
    <title>Calcutta Public School > Site Map</title>
<link rel="stylesheet" href="site_map.css">
  </head>
  <body>

<!------------Header section Start------------------->

<div id="fullpage">
<header>
<div class="logo"><img src="images/top.jpg" alt="logo"></div>
</header>
<!------------Main section Start------------------->

<div class="parent">
    <div class="div1"><nav id="nav" >
 <ul class="nav-links">
                                            <li><a href="index.html">Home</a></li>
                                            <li><a href="vision.html">Vision</a></li>
                                            <li><a href="history.html">History</a></li>
                                            <li><a href="location.html">Location</a></li>
                                            <li><a href="organisation.html">Organisation</a></li>
                                            <li><a href="curriculum.html">Curriculum</a></li>
                                            <li><a href="school_uniform.html">School Uniform</a></li>
                                            <li><a href="teaching_staff.html">Teaching Staff</a></li>
                                            <li><a href="facilities.html">Facilities</a></li>
                                            <li><a href="activities.html">Activities</a></li>
                                            <li><a href="rules.html">Rules</a></li>
                                            <li><a href="register_online.html">Register online</a></li>
                                            <li><a href="photogallery.html">Photogallery</a></li>
                                            <li><a href="contact_us.html">Contact Us</a></li>
                                            <li><a href="site_map.html">Site Map</a></li>
</ul>
</nav>
</div>
    <div class="div2"><p><font><strong class="vision">Site Map</font></strong><div class="vision-border"></div></p>
</div>
    <div class="div3">
<div class="para1"><a href="index.html" class="aMail">HOME</a></div>
<div class="main">
<div class="Lside">
<ul>
<li><a href="vision.html" class="aMail">VISION</a></li>
<li><a href="location.html" class="aMail">LOCATION</a></li>
<li><a href="curriculum.html" class="aMail">CURRICULUM</a></li>
<li><a href="teaching_staff.html" class="aMail">TEACHING STAFF</a></li>
<li><a href="activities.html" class="aMail">ACTIVITIES</a></li>
<li><a href="register_online.html" class="aMail">REGISTER ONLINE</a></li>
<li><a href="photogallery.html" class="aMail">PHOTOGALLERY</a></li>
</ul>
</div>
<div class="Rside">
<ul>
<li><a href="history.html" class="aMail">History</a></li>
<li><a href="organisation.html" class="aMail">ORGANISATION</a></li>
<li><a href="school_uniform.html" class="aMail">
SCHOOL UNIFORM</a></li>
<li><a href="facilities.html" class="aMail">
FACILITIES</a></li>
<li><a href="rules.html" class="aMail">
RULES</a></li>
<li><a href="contact_us.html" class="aMail">CONTACT US</a></li>
<li><a href="site_map.html" class="aMail">
SITE MAP</a></li>
</ul>
</div>
</div>

</div>
    <div class="div4"><footer class="footer">
<p>Powered by&nbsp<a href="https://www.google.com" target="_blank" class="afoot">Google.com</a></p>
</footer></div>
</div>
    

</div>
  </body>
</html>




* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html, body {
    font-family: Verdana, sans-serif;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    overflow-x: hidden;
overflow-y:scroll;
}

body {
    overflow: hidden;
}

.logo img {
    width: 780px;
    height: 108px;
}

#fullpage {
    background: url('images/bg_watermark.jpg') repeat-y;
    width: 780px;
}

img{
display:block;
width:100%;
}

a {
    text-decoration: none;
    color: #f8cf44;
    font-size: 10px;
    font-weight: 700;
    transition: color 0.3s ease;
}

a:hover {
    color: #fff;
}

.afoot {
    color: #000;
}

.afoot:hover {
    color: red;
}

.aMail,.aMail2{
 font-size: 13px;
    color: #fff;
font-weight:900;
transition: color 0.3s ease;
}
.aMail2{
margin-left:16.3%;
}

.aMail:hover, .aMail2:hover{
color: #f8cf44;
}

.vision {
    position: absolute;
    width: 100%;
    height: 34px;
    color: #FFD700;
    padding: 12px 10px 0;
    font-weight: 900;
    letter-spacing: 1.6px;
    font-size: 13.9px;
    overflow: hidden;
margin-top:-2px;
}

.vision-border {
    margin-top:29.2px;
margin-left: -10px;
display: inline-block;
background: rgb(7,13,86);
background: linear-gradient(131deg, rgba(7,13,86,1) 1%, rgba(45,68,136,1) 8%, rgba(46,60,135,1) 90%, rgba(7,13,86,1) 94%);
height:1px;
padding-left:210px;
}

p {
    font-size: 13px;
    color: #fff;
    line-height: 20px;
    word-spacing: 1px;
}

ul {
    margin-top: -3px;
}

ul li {
    list-style-type: none;
}

#nav {
    background: url('images/extra.jpg') repeat-y;
    min-width: 159px;
    height: 100%;
    padding: 14px 14.2px;
}

.nav-links {
    position: sticky;
}

.main {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
margin-bottom:27px;
}

.Lside, .Rside{
padding-top:15px;
}

.Lside li, .Rside li{
padding:3.5px;
text-transform:uppercase;
}

.strong {
    color: #f8cf44;
    font-weight: 800;
    font-size: 20px;
}

.footer {
    background: url('images/bottom_img.jpg') no-repeat;
    width: 780px;
    height: 27px;
}

.footer p {
    color: #000;
    font-weight: 900;
    font-size: 10px;
    padding: 5px 12px;
    display: flex;
    align-items: center;
}

.para1{
width:450px;
padding:8px 0;
position: relative;
text-align:center;
font-weight:900;
color:#fff;
border-radius:2px;
    font-size: 13px;
margin:2px auto 0px;
border-bottom:0.1em solid #000;
}
.para3{
padding: 17px 125px;
    font-size: 13px;
} 

.chairman {
    float: right;
    width: 250px;
    height: 164px;
    margin: 12px 15px;
}
.map{
width: 580px;
    height: 264px;
}
.mapsection{
margin-bottom:20px;
}

.parent {
    display: grid;
    grid-template-columns: 169px 1fr;
    grid-template-rows: auto;
    gap: 0;
}

.div1 {
    grid-column: 1 / 2;
    grid-row: 1 / span 5;
}

.div2 {
    grid-column: 2 / 3;
    grid-row: 1 / 2;
    height: 40px;
}

.div3 {
    padding: 10px;
margin-right:15px;
    grid-column: 2 / 3;
    grid-row: 2 / span 3;
}

.div4 {
    margin-top: -5px;
    grid-column: 1 / -1;
    grid-row: 6 / 7;
}



<!DOCTYPE html>
<html>
  <head>
    <title>Calcutta Public School > Contact Us</title>
<link rel="stylesheet" href="contact_us.css">
  </head>
  <body>

<!------------Header section Start------------------->

<div id="fullpage">
<header>
<div class="logo"><img src="images/top.jpg" alt="logo"></div>
</header>
<!------------Main section Start------------------->

<div class="parent">
    <div class="div1"><nav id="nav" >
 <ul class="nav-links">
                                            <li><a href="index.html">Home</a></li>
                                            <li><a href="vision.html">Vision</a></li>
                                            <li><a href="history.html">History</a></li>
                                            <li><a href="location.html">Location</a></li>
                                            <li><a href="organisation.html">Organisation</a></li>
                                            <li><a href="curriculum.html">Curriculum</a></li>
                                            <li><a href="school_uniform.html">School Uniform</a></li>
                                            <li><a href="teaching_staff.html">Teaching Staff</a></li>
                                            <li><a href="facilities.html">Facilities</a></li>
                                            <li><a href="activities.html">Activities</a></li>
                                            <li><a href="rules.html">Rules</a></li>
                                            <li><a href="register_online.html">Register online</a></li>
                                            <li><a href="photogallery.html">Photogallery</a></li>
                                            <li><a href="contact_us.html">Contact Us</a></li>
                                            <li><a href="site_map.html">Site Map</a></li>
</ul>
</nav>
</div>
    <div class="div2"><p><font><strong class="vision">Contact Us</font></strong><div class="vision-border"></div></p>
</div>
    <div class="div3">
<div class="para1">CALCUTTA PUBLIC SCHOOL</div>
<p class="para3">Mr. B. Jha (Chairman)<br>
Mr. B.N. Jha (Principal)<br>
Aswini Nagar, Baguiati<br>
Calcutta - 700 059<br>
Phone : +91-33-25717391 / 25911472<br>
Fax : +91-33-25910318<br>
E-mail:<a href="mailto:chairman@jetcps.org" class="aMail"> chairman@jetcps.org</a><br>
<a href="mailto:principal@jetcps.org" class="aMail2">principal@jetcps.org</a></p>
</div>
    <div class="div4"><footer class="footer">
<p>Powered by&nbsp<a href="https://www.google.com" target="_blank" class="afoot">Google.com</a></p>
</footer></div>
</div>
    

</div>
  </body>
</html>



* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html, body {
    font-family: Verdana, sans-serif;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    overflow-x: hidden;
overflow-y:scroll;
}

body {
    overflow: hidden;
}

.logo img {
    width: 780px;
    height: 108px;
}

#fullpage {
    background: url('images/bg_watermark.jpg') repeat-y;
    width: 780px;
}

img{
display:block;
width:100%;
}

a {
    text-decoration: none;
    color: #f8cf44;
    font-size: 10px;
    font-weight: 700;
    transition: color 0.3s ease;
}

a:hover {
    color: #fff;
}

.afoot {
    color: #000;
}

.afoot:hover {
    color: red;
}

.aMail,.aMail2{
 font-size: 13px;
    color: #fff;
font-weight:normal;
transition: color 0.3s ease;
}
.aMail2{
margin-left:16.3%;
}

.aMail:hover, .aMail2:hover{
color: #f8cf44;
}

.vision {
    position: absolute;
    width: 100%;
    height: 34px;
    color: #FFD700;
    padding: 12px 10px 0;
    font-weight: 900;
    letter-spacing: 1.6px;
    font-size: 13.9px;
    overflow: hidden;
margin-top:-2px;
}

.vision-border {
    margin-top:29.2px;
margin-left: -10px;
display: inline-block;
background: rgb(7,13,86);
background: linear-gradient(131deg, rgba(7,13,86,1) 1%, rgba(45,68,136,1) 8%, rgba(46,60,135,1) 90%, rgba(7,13,86,1) 94%);
height:1px;
padding-left:210px;
}

p {
    font-size: 13px;
    color: #fff;
    line-height: 20px;
    word-spacing: 1px;
}

ul {
    margin-top: -3px;
}

ul li {
    list-style-type: none;
}

#nav {
    background: url('images/extra.jpg') repeat-y;
    min-width: 159px;
    height: 100%;
    padding: 14px 14.2px;
}

.nav-links {
    position: sticky;
}

.main {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
}

.strong {
    color: #f8cf44;
    font-weight: 800;
    font-size: 20px;
}

.footer {
    background: url('images/bottom_img.jpg') no-repeat;
    width: 780px;
    height: 27px;
}

.footer p {
    color: #000;
    font-weight: 900;
    font-size: 10px;
    padding: 5px 12px;
    display: flex;
    align-items: center;
}

.para1{
width:400px;
padding:8px 0;
position: relative;
text-align:center;
font-weight:900;
color:#000;
border-radius:2px;
background:#a9c2fa;
    font-size: 18px;
margin:13px auto 0px;
}
.para3{
padding: 17px 125px;
    font-size: 13px;
} 

.chairman {
    float: right;
    width: 250px;
    height: 164px;
    margin: 12px 15px;
}
.map{
width: 580px;
    height: 264px;
}
.mapsection{
margin-bottom:20px;
}

.parent {
    display: grid;
    grid-template-columns: 169px 1fr;
    grid-template-rows: auto;
    gap: 0;
}

.div1 {
    grid-column: 1 / 2;
    grid-row: 1 / span 5;
}

.div2 {
    grid-column: 2 / 3;
    grid-row: 1 / 2;
    height: 40px;
}

.div3 {
    padding: 10px;
margin-right:15px;
margin-bottom:11px;
    grid-column: 2 / 3;
    grid-row: 2 / span 3;
}

.div4 {
    margin-top: -5px;
    grid-column: 1 / -1;
    grid-row: 6 / 7;
}
