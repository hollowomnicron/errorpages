# Funny Error Page
A Funny Error Page Application Addon in PHP
There are multiple ways to Integrate this into your system



Create a Function

<code>
  
    function Error($type){
    include"return_error.php";
    }
    
  </code>
  
  
  Or By .htaccess
  
  
  <code>
  ErrorDocument 404 /path/to/return_error.php
  </code>
