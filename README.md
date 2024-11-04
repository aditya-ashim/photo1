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



