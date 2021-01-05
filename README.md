# Prediction Tool for Early Detection of Diabetes

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Prediction Tool for Early detection of Diabetes</title>
<body>
    Hello, The One Who Concerning Your Own Health!

    <h1>David Intelligent Healthcare Limited</h1>

<p>Our company, David Intelligent Healthcare Limited is the data science start-up company who has the vision of enhancing the accessibility for patients and doctors 
    in Hong Kong Healthcare Industry. </p>
    
    <p>We believe that "Better access and communication between patients and doctors should have positive effect to the healthcare ecosystem." </p>

    <p>Diabetes Mellitus (DM) is one of the top chronic disease in the world. 
      The worldwide diabetic patients have reached 382 million in 2013 and predicted that the prevalence will increase 55% in 2035. 
      Also, it claimed that every 6 to 10 seconds, one death exists (Lukmanto & Irwansyah, 2015).</p>
    
    <p>DM is the disease that the pancreas doesn’t produce insulin to convert glucose. 
      Then, excessive glucose in the bloodstream will trigger different severe complications or life-threatening health problems such neuropathy, nephropathy and retinopathy. 
      There are two types of DM: insulin-dependent DM (Type 1 Diabetes or called T1D) and non-insulin-dependent DM (Type 2 Diabetes or called T2D). 
      Approximately 90% of patients have T2D (Chaki et al., 2020 & Kavakiotis et al., 2017).</p>


           
     <p>References:</p>
     <p>1) Chaki, J., Ganesh, S.T. & Cidham, S.K. et al. (2020), "Machine learning and artificial
        intelligence based diabetes mellitus detection and self-management: A systematic review",
        Journal of King Saud University - Computer and Information Sciences, available online 4
        July, pp. 1-21.
        </p>
     <p>2) Kavakiotis, I., Tsave, O. & Salifoglou, A. et al. (2017), "Machine learning and data mining
        methods in diabetes research", Computational and Structural Biotechnology Journal, vol.
        15, pp. 104-116.</p>
     <p>3) Lukmanto, R.B. & Irwansyah, E. (2015), "The early detection of diabetes mellitus (DM)
        using fuzzy hierarchical model", Procedia Computer Science, vol. 59, pp. 312-319.</p>

        

     <body style = "text-align:left;"> 
          
        <h2 style = "color:blue;" >  
          Prediction Tool for Early Detection of Diabetes 
        </h2> 
          
        <p id = "GFG_UP" style = 
            "font-size: 19px; font-weight: bold;"> 
        </p> 
          
        <button onclick = "GFG_Fun()"> 
            click here 
        </button> 
          
        <p id = "GFG_DOWN" style = 
            "color: green; font-size: 24px; font-weight: bold;"> 
        </p> 
          
        <script> 
            var el_up = document.getElementById("GFG_UP"); 
            var el_down = document.getElementById("GFG_DOWN"); 
              
            el_up.innerHTML = "If you have increased thirst, increased urination, increased hunger or already suspect getting Diabetes, " 
                    + "Click the Following Button."; 
     
            function GFG_Fun() { 
                  
                // Create anchor element. 
                var a = document.createElement('a');  
                  
                // Create the text node for anchor element. 
                var link = document.createTextNode("Go for 1-Minute Test"); 
                  
                // Append the text node to anchor element. 
                a.appendChild(link);  
                  
                // Set the title. 
                a.title = "If you get POSITIVE, go to visit Endocrinologist for further checking; If you get NEGATIVE, keep healthy lifestyle and regular body check."  
                  
                // Set the href property. 
                a.href = "https://go.rapidminer.com/am/simulator/07d4d74a-dd6c-4534-9ab8-89cf29590675";  
                  
                // Append the anchor element to the body. 
                document.body.appendChild(a);  
            } 
        </script>  


    </body>  
</html>                     
