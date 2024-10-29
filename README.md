<html>

<head>
<meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
<title>Calcutta Public School > Photogallery</title>
<style>
  .aa {
    color: #F8CF44;
    font-family: verdana;
    font-size: 10px;
    font-weight: bold;
    text-decoration: none;
  }

  .aa:hover {
    color: #FFFFFF;
    font-family: verdana;
    font-size: 10px;
    font-weight: bold;
    text-decoration: none;
  }

  /* Modal styling using table */
  .modal-table {
    display: none; /* Hidden by default */
    position: fixed;
    z-index: 1;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(128, 128, 128, 0.9); /* Gray with opacity */
  }

  .modal-content-table {
    width: 80%;
    max-width: 700px;
    margin: 0 auto;
    text-align: center;
  }

  .close, .prev, .next {
    color: #fff;
    font-size: 30px;
    font-weight: bold;
    cursor: pointer;
  }

  .close {
    position: absolute;
    top: 20px;
    right: 35px;
  }

  .prev, .next {
    font-size: 40px;
    font-weight: bold;
  }

  .prev {
    position: absolute;
    left: 20px;
    top: 50%;
    transform: translateY(-50%);
  }

  .next {
    position: absolute;
    right: 20px;
    top: 50%;
    transform: translateY(-50%);
  }
</style>
</head>

<body topmargin="0" leftmargin="0" background="../images/inner/bg_watermark.jpg" bgproperties="fixed">
<table border="0" cellpadding="0" cellspacing="0" width="780">
  <tr>
    <td width="780"><img border="0" src="../images/top.jpg" width="780" height="108"></td>
  </tr>
  <tr>
    <td width="780">
      <table border="0" cellpadding="0" cellspacing="0" width="780">
        <tr>
          <td width="159" height="265" valign="top" background="../images/inner/extra.jpg">
            <p align="justify" style="line-height: 140%; margin-left: 20; margin-top: 20; margin-bottom: 0">                             
              <a class="aa" href="../home.htm">Home</a><br>
              <a class="aa" href="vision.htm">Vision</a><br>
              <a class="aa" href="history.htm">History</a><br>
              <a class="aa" href="location.htm">Location</a><br>
              <a class="aa" href="organisation.htm">Organisation</a><br>
              <a class="aa" href="curriculum.htm">Curriculum</a><br>
              <a class="aa" href="school.htm">School Uniform</a><br>
              <a class="aa" href="teaching.htm">Teaching Staff</a><br>
              <a class="aa" href="fac.htm">Facilities</a><br>
              <a class="aa" href="activities.htm">Activities</a><br>
              <a class="aa" href="rules.htm">Rules</a><br>
              <a class="aa" href="register.htm">Register online</a><br>
              <a class="aa" href="photo.htm">Photogallery</a><br>
              <a class="aa" href="contact.htm">Contact Us</a><br>
              <a class="aa" href="site.htm">Site Map</a></td>
          <td width="621" valign="top">
            <table border="0" cellpadding="0" cellspacing="0" width="621">
              <tr>
                <td width="621"><img border="0" src="../images/inner/photogallery_img.jpg" width="621" height="34"></td>
              </tr>
              <tr>
                <td width="621">
                  <center>
                    <table border="0" cellpadding="0" cellspacing="0" width="581">
                      <tr>
                        <td colspan="2" align="center" height="30"><font color="#FFFFFF" size="2" face="Verdana"><b>ANNUAL
                            FUNCTION<br><br></b></font></td>
                      </tr>
                      <tr>
                        <td align="center"><img onclick="openModal(0)" style="cursor: pointer; border:1 solid #FFFFFF" src="../images/stage.gif" width="250" height="164"></td>
                        <td align="center"><img onclick="openModal(1)" style="cursor: pointer; border:1 solid #FFFFFF" src="../images/drama_4.gif" width="250" height="164"></td>
                      </tr>
                      <tr>
                        <td align="center"><img onclick="openModal(2)" style="cursor: pointer; border:1 solid #FFFFFF" src="../images/drama_3.gif" width="250" height="164"></td>
                        <td align="center"><img onclick="openModal(3)" style="cursor: pointer; border:1 solid #FFFFFF" src="../images/dance.gif" width="250" height="164"></td>
                      </tr>
                    </table>
                  </center>
                </td>
              </tr>
            </table>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>

<!-- Modal Table -->
<table id="myModal" class="modal-table">
  <tr>
    <td align="center">
      <table class="modal-content-table">
        <tr>
          <td align="left"><span class="prev" onclick="prevImage()">&#10094;</span></td>
          <td>
            <img id="modalImage" width="500" height="400" style="border:2px solid #FFFFFF;">
          </td>
          <td align="right"><span class="next" onclick="nextImage()">&#10095;</span></td>
        </tr>
        <tr>
          <td colspan="3" align="center"><span class="close" onclick="closeModal()">&times;</span></td>
        </tr>
      </table>
    </td>
  </tr>
</table>

<script>
  // Array of image sources
  const images = [
    "../images/stage.gif",
    "../images/drama_4.gif",
    "../images/drama_3.gif",
    "../images/dance.gif"
  ];
  
  // Variable to keep track of the current image index
  let currentIndex = 0;

  // Function to open the modal and display the clicked image
  function openModal(index) {
    currentIndex = index;
    document.getElementById("myModal").style.display = "table";
    document.getElementById("modalImage").src = images[currentIndex];
  }

  // Function to close the modal
  function closeModal() {
    document.getElementById("myModal").style.display = "none";
  }

  // Function to show the previous image
  function prevImage() {
    currentIndex = (currentIndex === 0) ? images.length - 1 : currentIndex - 1;
    document.getElementById("modalImage").src = images[currentIndex];
  }

  // Function to show the next image
  function nextImage() {
    currentIndex = (currentIndex === images.length - 1) ? 0 : currentIndex + 1;
    document.getElementById("modalImage").src = images[currentIndex];
  }
</script>

</body>
</html>


<script>
  // Array of image sources
  const images = [
    "../images/stage.gif",
    "../images/drama_4.gif",
    "../images/drama_3.gif",
    "../images/dance.gif"
  ];
  
  // Variable to keep track of the current image index
  let currentIndex = 0;

  // Function to open the modal and display the clicked image
  function openModal(index) {
    currentIndex = index;
    document.getElementById("myModal").style.display = "table";
    document.getElementById("modalImage").src = images[currentIndex];
    updateButtons(); // Call function to update button visibility
  }

  // Function to close the modal
  function closeModal() {
    document.getElementById("myModal").style.display = "none";
  }

  // Function to show the previous image
  function prevImage() {
    if (currentIndex > 0) {
      currentIndex--;
      document.getElementById("modalImage").src = images[currentIndex];
      updateButtons();
    }
  }

  // Function to show the next image
  function nextImage() {
    if (currentIndex < images.length - 1) {
      currentIndex++;
      document.getElementById("modalImage").src = images[currentIndex];
      updateButtons();
    }
  }

  // Function to update the visibility of previous and next buttons
  function updateButtons() {
    document.querySelector(".prev").style.display = currentIndex === 0 ? "none" : "inline";
    document.querySelector(".next").style.display = currentIndex === images.length - 1 ? "none" : "inline";
  }

  // Event listener for keydown to close modal on Esc key press
  document.addEventListener('keydown', function(event) {
    if (event.key === "Escape") {
      closeModal();
    }
  });
</script>
