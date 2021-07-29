# CSS

Media queries (FROM TRANSPARENT LOGIN PROJECT)


      @media only screen  and (min-width: 1200px) {
      
      .container{
            top: 25%;
            left: 36%;
      }
    }

      @media only screen and (max-width: 840px) {
      
      .container{
            top: 30%;
            left: 20%;
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

    @media only screen and (max-width: 600px) {
      
      .container{
            top: 28%;
            left: 11%;
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

      @media only screen and (max-width: 470px) {
      
      .container{
            top: 32%;
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

FOR DARKEN BACKGROUND IMAGE WITHOUT CONTENT EFFCET

      body {
      background: url(11.jpg) no-repeat center center fixed rgba(0, 0, 0, 0.5) ;
      background-size: cover;
      background-blend-mode: darken;

}

letter-spacing

      .contact-title h2{
      font-size: 16px;
      line-height: 10px;
      font-weight: 600;
      letter-spacing: 2px;

}
