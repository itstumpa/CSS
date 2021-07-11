# CSS

@Media queries (FROM TRANSPARENT LOGIN PROJECT)



@media only screen  and (min-width: 1200px) {
      .container{
            top: 25%;
            left: 41%;
      }
    }

@media only screen and (max-width: 800px) {
      .container{
            top: 25%;
            left: 35%;
      }   
    }
    @media only screen and (max-width: 600px) {
      .container{
            top: 28%;
            left: 25%;
      }
      .container h1{
            width:53%;
            font-size: 26px;
            margin-bottom: 10px;
            padding: 1px 0;
      }
      .box input{
            font-size: 18px;
      }
    }
@media only screen and (max-width: 450px) {    
      .container{
            top: 28%;
            left: 30%;
      }
      .container h1{
            width:72%;
            font-size: 26px;
            margin-bottom: 10px;
            padding: 5px 0;
            border-bottom:3px solid purple;
      }
      .box{
            width: 90%;
            margin: 9px 0px;
            border-bottom: 1px solid purple;
      }      
      .box input{
            width: 100%;
            padding: 3px 0px;
            font-size: 15px;
      }
      .box i{
            display: none;
      }
      .btn{
            font-size: 14px;
            margin: 8px 0;
            padding: 6px 10px;
      }      
    }
    
    
  FOR BODY IMAGE
  
    body { 
    background-image: url(/assets/img/living.jpg); 
    background-repeat: no-repeat; 
    background-position: center;
    background-attachment: fixed;       
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    height:100%;
    width:100%; 
}   
