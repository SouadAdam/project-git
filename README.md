github-final-project

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class='container'>
        <div class='ct-inner'>
        
        <!-- Project HTML Below -->
        <div class='calculator'>
         <div class='inner'>
          
          <div class='innerIn'>
           <div class='screen active'>
             <div class='output'>0</div>
             <div class='output line2'>-</div>
             <div class='output line3'>-</div>
             <div class='screen-layer'></div>
           </div>
           
           
           
           <div class='controls'>
             
             
            <div class='num-pad'>
             <div class='button numbers small'>1</div>
             <div class='button numbers small'>2</div>
             <div class='button numbers small'>3</div>
             <div class='button numbers small'>4</div>
             <div class='button numbers small'>5</div>
             <div class='button numbers small'>6</div>
             <div class='button numbers small'>7</div>
             <div class='button numbers small'>8</div>
             <div class='button numbers small'>9</div>
             <div class='button numbers big zeroBtn btnLeftAligned'>0</div>
             <div class='button numbers small'>.</div>
            </div>
            
            <div class='control-pad operator-pad1'>
               <div class='button med oper'>+</div>
               <div class='button med oper'>-</div>
               <div class='button med oper'>÷</div>
               <div class='button med oper'>=</div>
            </div>
             
           </div>
           
           
           
          </div> <!-- Inner in End -->
            
         </div>
        </div>
    
        
        
        
        <!-- Project HTML Above -->
        
        <div class='by-dev'>
          <span class='by-text'>by</span>
          <span class='by-val'>Deepak Kamat</span>
          <span class='by-site'><a href='http://www.stramaxon.com'>stramaxon.com</a></span>
        </div>
    
    
        </div>
        </div>
</body>
</html>


/* Page Layout CSS */

htm, body {
    background-color:#000;
    background: rgb(114,114,114); /* Old browsers */
    background: -moz-radial-gradient(center, ellipse cover, rgba(114,114,114,1) 0%, rgba(30,30,30,1) 100%); /* FF3.6+ */
    background: -webkit-gradient(radial, center center, 0px, center center, 100%, color-stop(0%,rgba(114,114,114,1)), color-stop(100%,rgba(30,30,30,1))); /* Chrome,Safari4+ */
    background: -webkit-radial-gradient(center, ellipse cover, rgba(114,114,114,1) 0%,rgba(30,30,30,1) 100%); /* Chrome10+,Safari5.1+ */
    background: -o-radial-gradient(center, ellipse cover, rgba(114,114,114,1) 0%,rgba(30,30,30,1) 100%); /* Opera 12+ */
    background: -ms-radial-gradient(center, ellipse cover, rgba(114,114,114,1) 0%,rgba(30,30,30,1) 100%); /* IE10+ */
    background: radial-gradient(ellipse at center, rgba(114,114,114,1) 0%,rgba(30,30,30,1) 100%); /* W3C */
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#727272', endColorstr='#1e1e1e',GradientType=1 ); /* IE6-9 fallback on horizontal gradient */
    }
    
    html {
        height: auto;
    }
        
    
    body {
        font:16px normal normal "Open Sans", sans-serif;
        margin:0px;
        color:#fff;
    }
    
    
    .container {padding:20px;margin:0 auto;}
    
    .calculator {margin:0 auto;} /* Centering */
    .calculator {box-shadow:inset 0px 0px 40px rgba(0,0,0,0.1), 30px 30px 60px rgba(0,0,0,0.5) !important;}
    
    
    
    /* Calculator CSS */
    
    .calculator {
      width:400px;
      min-height:500px;
      font-family:"Lucida Sans Unicode", "Lucida Grande", sans-serif;
      border:1px solid #ccc;
      border-radius:5px;
      box-shadow:inset 0px 0px 40px rgba(0,0,0,0.1);
     background: rgb(183,183,183); /* Old browsers */
    background: -moz-linear-gradient(left, rgba(183,183,183,1) 1%, rgba(201,201,201,1) 52%, rgba(160,160,160,1) 100%, rgba(196,196,196,1) 100%); /* FF3.6+ */
    background: -webkit-gradient(linear, left top, right top, color-stop(1%,rgba(183,183,183,1)), color-stop(52%,rgba(201,201,201,1)), color-stop(100%,rgba(160,160,160,1)), color-stop(100%,rgba(196,196,196,1))); /* Chrome,Safari4+ */
    background: -webkit-linear-gradient(left, rgba(183,183,183,1) 1%,rgba(201,201,201,1) 52%,rgba(160,160,160,1) 100%,rgba(196,196,196,1) 100%); /* Chrome10+,Safari5.1+ */
    background: -o-linear-gradient(left, rgba(183,183,183,1) 1%,rgba(201,201,201,1) 52%,rgba(160,160,160,1) 100%,rgba(196,196,196,1) 100%); /* Opera 11.10+ */
    background: -ms-linear-gradient(left, rgba(183,183,183,1) 1%,rgba(201,201,201,1) 52%,rgba(160,160,160,1) 100%,rgba(196,196,196,1) 100%); /* IE10+ */
    background: linear-gradient(to right, rgba(183,183,183,1) 1%,rgba(201,201,201,1) 52%,rgba(160,160,160,1) 100%,rgba(196,196,196,1) 100%); /* W3C */
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#b7b7b7', endColorstr='#c4c4c4',GradientType=1 ); /* IE6-9 */
    }
    
    
    .calculator .inner {
      padding:10px;
    }
    
    .calculator .screen {
      padding:5px 10px;
      font-size:24px;
      border-radius:5px /* 5px 0px 0px */;
      color:#fff;
      border:1px solid #195739;
      position:relative;
      background-color:#2A8358;
      margin-bottom:10px;
      text-align:right;
      box-shadow:inset 0px 2px 2px rgba(0,0,0,0.7), 0px 2px 1px #eee;
    }
    
    .screen .output {
    position:relative;
      text-shadow:0px 0px 2px #DFFF5F;
    }
    .screen .screen-layer {
      position:absolute;
      border-radius:5px;
      top:0px;right:0px;left:0px;bottom:0px;
    background: -moz-linear-gradient(top, rgba(174,188,191,0.29) 0%, rgba(117,124,122,0.19) 50%, rgba(10,14,10,0.19) 51%, rgba(10,8,9,0.08) 100%); /* FF3.6+ */
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(174,188,191,0.29)), color-stop(50%,rgba(117,124,122,0.19)), color-stop(51%,rgba(10,14,10,0.19)), color-stop(100%,rgba(10,8,9,0.08))); /* Chrome,Safari4+ */
    background: -webkit-linear-gradient(top, rgba(174,188,191,0.29) 0%,rgba(117,124,122,0.19) 50%,rgba(10,14,10,0.19) 51%,rgba(10,8,9,0.08) 100%); /* Chrome10+,Safari5.1+ */
    background: -o-linear-gradient(top, rgba(174,188,191,0.29) 0%,rgba(117,124,122,0.19) 50%,rgba(10,14,10,0.19) 51%,rgba(10,8,9,0.08) 100%); /* Opera 11.10+ */
    background: -ms-linear-gradient(top, rgba(174,188,191,0.29) 0%,rgba(117,124,122,0.19) 50%,rgba(10,14,10,0.19) 51%,rgba(10,8,9,0.08) 100%); /* IE10+ */
    background: linear-gradient(to bottom, rgba(174,188,191,0.29) 0%,rgba(117,124,122,0.19) 50%,rgba(10,14,10,0.19) 51%,rgba(10,8,9,0.08) 100%); /* W3C */
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#4aaebcbf', endColorstr='#140a0809',GradientType=0 ); /* IE6-9 */
      
    }
    
    
    /* Button */
    .calculator .button {
      font-size:18px;
      margin:4px 2px;
      text-align:center;
      width:80px;
      background-color:#ccc;
      color:#111;
      border:1px solid ;
      box-sizing:border-box;
    background: rgb(242,242,242); /* Old browsers */
    background: -moz-linear-gradient(top, rgba(242,242,242,1) 0%, rgba(219,219,219,1) 100%); /* FF3.6+ */
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(242,242,242,1)), color-stop(100%,rgba(219,219,219,1))); /* Chrome,Safari4+ */
    background: -webkit-linear-gradient(top, rgba(242,242,242,1) 0%,rgba(219,219,219,1) 100%); /* Chrome10+,Safari5.1+ */
    background: -o-linear-gradient(top, rgba(242,242,242,1) 0%,rgba(219,219,219,1) 100%); /* Opera 11.10+ */
    background: -ms-linear-gradient(top, rgba(242,242,242,1) 0%,rgba(219,219,219,1) 100%); /* IE10+ */
    background: linear-gradient(to bottom, rgba(242,242,242,1) 0%,rgba(219,219,219,1) 100%); /* W3C */
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f2f2f2', endColorstr='#dbdbdb',GradientType=0 ); /* IE6-9 */
      border:0px solid #eee;
      box-shadow:0px 0px 3px #000, 0px 2px 1px #fff,inset 0px 3px 1px #fff, inset 0px 0px 2px #999;
      border-radius:5px;
      cursor:pointer;
      font-weight:800;
      text-shadow:1px 0px 0px #fff;
    }
    
    .calculator .button:active {
      box-shadow:0px 0px 3px #000, 0px 2px 1px #fff,inset 0px 1px 2px #999, inset 0px 0px 2px #eee;
    }
    
    
    .calculator .button.btnLeftAligned {
      text-align:left;
      padding-left:35px;
    } 
    
    
    /* Numbad */
    .num-pad {
      display:inline-block;
      max-width:262px;
      vertical-align:top;
    }
    .num-pad .button {
      display:inline-block;
      padding:5px 0px;
    }
    
    .num-pad .zeroBtn {
      width:169px;
    }
    
    
    /* Operator Pad Num 1 */
    .operator-pad1 {
      display:inline-block;
      vertical-align:top;
      width:108px;
    }
    .operator-pad1 .button:first-child{margin-top:4px;}
    .operator-pad1 .button {
    width:109px;
    padding:5px 0px; 
    margin:8px 2px;
    }
    
    
    
    
    
    .by-dev {text-align:center;margin:20px 0;}
    .by-dev span {font-family:"Segoe UI",Arial,sans-serif;}
    .by-dev .by-text {font-size:30px;display:block;opacity:0.5;}
    .by-dev .by-val {font-size:80px;display:block;opacity:0.2;
      text-shadow:0 0 30px rgba(255,255,255,0.7),1px 1px 0px #000;
    }
    .by-site  a {color:#fff;text-decoration:none;color:rgba(255,255,255,0.4);
    border-bottom:1px solid #999;
    }
