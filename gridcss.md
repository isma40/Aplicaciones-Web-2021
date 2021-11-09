.parent {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 1fr);
    grid-column-gap: 0px;
    grid-row-gap: 0px;
    border:1px solid black;
  
    }
    
    .div1 {
       grid-area: 1 / 1 / 2 / 2; 
       border:1px solid blue;
      }
    .div2 { 
      grid-area: 2 / 1 / 3 / 2; 
      border:1px solid blue;
    }
    .div3 { 
      grid-area: 2 / 1 / 5 / 2;
      border:1px solid blue;
     }
    .div4 { 
      grid-area: 2 / 2 / 5 / 5;
      border:1px solid blue;
    }
    .div5 { 
      grid-area: 1 / 2 / 2 / 3;
      border:1px solid blue;
     }
    .div6 { 
      grid-area: 1 / 2 / 2 / 4;
      border:1px solid blue;
    }
    
    body{
      margin: 0px;
      padding: 0px;
      background: yellow;
      font-family: 'Lato', sans-serif;
    }
    
    nav{
      float: none; 
      clear: both;
      width: 30%; 
      margin: 10% auto;
      background: #eeeeee;
    }
    
    nav ul {
      list-style: none;
      margin: 0px;
      padding: 0px;
    }
    
    nav li{
      float: none; 
      width: 100%;
    }
    
    nav li a{
      display: block; 
      width: 100%; 
      padding: 20px; 
      border-left: 5px solid; 
      position: relative; 
      z-index: 2;
      text-decoration: none;
      color: #444;
      box-sizing: border-box;  
      -moz-box-sizing: border-box;  
      -webkit-box-sizing: border-box; 
    }
      
    nav li a:hover{ border-bottom: 0px; color: #fff;}
    nav li:first-child a{ border-left: 10px solid #3498db; }
    nav li:nth-child(2) a{ border-left: 10px solid #ffd071; }
    nav li:nth-child(3) a{ border-left: 10px solid #f0776c; }
    nav li:last-child a{ border-left: 10px solid #1abc9c; }
    
    nav li a:after { 
      content: "";
      height: 100%; 
      left: 0; 
      top: 0; 
      width: 0px;  
      position: absolute; 
      transition: all 0.3s ease 0s; 
      -webkit-transition: all 0.3s ease 0s; 
      z-index: -1;
    }
    
    nav li a:hover:after{ width: 100%; }
    nav li:first-child a:after{ background: #3498db; }
    nav li:nth-child(2) a:after{ background: #ffd071; }
    nav li:nth-child(3) a:after{ background: #f0776c; }
    nav li:last-child a:after{ background: #1abc9c; }
    
    
    
    @font-face {
      font-family: 'Lato';
      font-style: normal;
      font-weight: 100;
      src: local('Lato Hairline'), local('Lato-Hairline'), url(http://themes.googleusercontent.com/static/fonts/lato/v6/boeCNmOCCh-EWFLSfVffDg.woff) format('woff');
    }
    @font-face {
      font-family: 'Lato';
      font-style: normal;
      font-weight: 300;
      src: local('Lato Light'), local('Lato-Light'), url(http://themes.googleusercontent.com/static/fonts/lato/v6/KT3KS9Aol4WfR6Vas8kNcg.woff) format('woff');
    }
    @font-face {
      font-family: 'Lato';
      font-style: normal;
      font-weight: 400;
      src: local('Lato Regular'), local('Lato-Regular'), url(http://themes.googleusercontent.com/static/fonts/lato/v6/9k-RPmcnxYEPm8CNFsH2gg.woff) format('woff');
    }
    @font-face {
      font-family: 'Lato';
      font-style: normal;
      font-weight: 700;
      src: local('Lato Bold'), local('Lato-Bold'), url(http://themes.googleusercontent.com/static/fonts/lato/v6/wkfQbvfT_02e2IWO3yYueQ.woff) format('woff');
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
    
  
   
    
    
    
    
    
   
 
 
