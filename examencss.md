body {
    background-color: lightblue;
  }
  * {
    box-sizing: border-box;
  }
  
  body {
    margin: 0;
  }
  
  /* Style the header */
  .header {
    background-color: #f1f1f1;
    padding: 20px;
    text-align: center;
  }
  
  /* Style the top navigation bar */
  .topnav {
    overflow: hidden;
    background-color: #333;
  }
  
  /* Style the topnav links */
  .topnav a {
    float: left;
    display: block;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }
  
  /* Change color on hover */
  .topnav a:hover {
    background-color: #ddd;
    color: black;
  }
  
  body {
    color: #333;
    font-family: 'Open Sans', sans-serif;
    font-weight: 300;
  }
  
  h1,
  h1+p {
    margin: 30px 15px 0;
    font-weight: 300;
  }
  h1+p a {
    color: #333;
  }
  h1+p a:hover {
    text-decoration: none;
  }
  h2 {
    margin: 60px 15px 0;
    padding: 0;
    font-weight: 300;
  }
  h2 span {
    margin-left: 1em;
    color: #aaa;
    font-size: 85%;
  }
  .column {
    margin: 15px 15px 0;
    padding: 0;
  }
  .column:last-child {
    padding-bottom: 60px;
  }
  .column::after {
    content: '';
    clear: both;
    display: block;
  }
  .column div {
    position: relative;
    float: left;
    width: 300px;
    height: 200px;
    margin: 0 0 0 25px;
    padding: 0;
  }
  .column div:first-child {
    margin-left: 0;
  }
  .column div span {
    position: absolute;
    bottom: -20px;
    left: 0;
    z-index: -1;
    display: block;
    width: 300px;
    margin: 0;
    padding: 0;
    color: #444;
    font-size: 18px;
    text-decoration: none;
    text-align: center;
    -webkit-transition: .3s ease-in-out;
    transition: .3s ease-in-out;
    opacity: 0;
  }
  figure {
    width: 300px;
    height: 200px;
    margin: 0;
    padding: 0;
    background: #fff;
    overflow: hidden;
  }
  figure:hover+span {
    bottom: -36px;
    opacity: 1;
  }
  
  
  
  /* Zoom In #1 */
  .hover01 figure img {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transition: .3s ease-in-out;
    transition: .3s ease-in-out;
  }
  .hover01 figure:hover img {
    -webkit-transform: scale(1.3);
    transform: scale(1.3);
  }

  body {
    color: #333;
    font-family: 'Open Sans', sans-serif;
    font-weight: 300;
  }
  h1,
  h1+p {
    margin: 30px 15px 0;
    font-weight: 300;
  }
  h1+p a {
    color: #333;
  }
  h1+p a:hover {
    text-decoration: none;
  }
  h2 {
    margin: 60px 15px 0;
    padding: 0;
    font-weight: 300;
  }
  h2 span {
    margin-left: 1em;
    color: #aaa;
    font-size: 85%;
  }
  .column {
    margin: 15px 15px 0;
    padding: 0;
  }
  .column:last-child {
    padding-bottom: 60px;
  }
  .column::after {
    content: '';
    clear: both;
    display: block;
  }
  .column div {
    position: relative;
    float: left;
    width: 300px;
    height: 200px;
    margin: 0 0 0 25px;
    padding: 0;
  }
  .column div:first-child {
    margin-left: 0;
  }
  .column div span {
    position: absolute;
    bottom: -20px;
    left: 0;
    z-index: -1;
    display: block;
    width: 300px;
    margin: 0;
    padding: 0;
    color: #444;
    font-size: 18px;
    text-decoration: none;
    text-align: center;
    -webkit-transition: .3s ease-in-out;
    transition: .3s ease-in-out;
    opacity: 0;
  }
  figure {
    width: 300px;
    height: 200px;
    margin: 0;
    padding: 0;
    background: #fff;
    overflow: hidden;
  }
  figure:hover+span {
    bottom: -36px;
    opacity: 1;
  }
 
  /* Zoom In #1 */
  .hover01 figure img {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transition: .3s ease-in-out;
    transition: .3s ease-in-out;
  }
  .hover01 figure:hover img {
    -webkit-transform: scale(1.3);
    transform: scale(1.3);
  }

  .hover01 figure img {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transition: .3s ease-in-out;
    transition: .3s ease-in-out;
  }
  .hover01 figure:hover img {
    -webkit-transform: scale(1.3);
    transform: scale(1.3);
  }

  table, th, td {
    border: 1px solid rgb(255, 0, 0);
  }
  
  table {
    width: 100%;
  }

  body {

    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}


.contact_form{
    width: 460px;
    height: auto;
    margin: 80px auto;
    border-radius: 10px;
    padding-top: 30px;
    padding-bottom: 20px;
    padding-left: 20px;
    background-color: rgb(11, 184, 184);

}

input {
    background-color: rgb(188, 157, 143);
    height: 40px;
    width: 408px;
    border-radius: 5px;
    border-style: solid;
    border-width: 1px;
    margin-top: 10px;
    margin-bottom: 10px;
    padding-left: 10px;

}

label {
    display: block;
    float: center;
}

textarea {
    background-color: darkseagreen;
    height: 130px;
    width: 408%;
    border-radius: 5px;
    border-style: solid;
    margin-top: 10px;
    padding-top: 5px;
    padding-left: 5px;
}

button {
    width: 420px;
    height: 45px;
    border-radius: 10px;
    border-style: solid;
    border: 1px solid;
    margin-top: 10px;
    margin-bottom: 20px;
    transition: 0.5 ease-in;
}


button:hover {
    height: 50px;
    background-color: lightgray;
}

textarea:focus{
    outline:0;
    background-color: white;
    border: 3px solid rgb(red, green, blue);
}
