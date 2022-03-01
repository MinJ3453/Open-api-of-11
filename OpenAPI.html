<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="shortcut icon" href="/favicon.ico" type="image/x-icon">
<link rel="icon" href="/favicon.ico" type="image/x-icon">

    <title>Document</title>
</head>

<body>
    
       
    <input type="text" id="input">
    <button onclick="input()">검색</button>
     

    <script src="https://code.jquery.com/jquery-3.4.1.js"
        integrity="sha256-WpOohJOqMqqyKL9FccASB9O0KwACQJpFTUBLTYOVvVU=" crossorigin="anonymous">
    </script>
    
 
    <script type="text/javascript"> //cors로 인해 막혀서 우회사이트 돌려서 실행
 
 var temp;

function input(){
var input = document.getElementById("input").value;
temp = input;



  $(document).ready(function(){
   
        $.ajax({
            method: "POST",
            url: "https://cors-anywhere.herokuapp.com/https://openapi.11st.co.kr/openapi/OpenApiService.tmall?key=(얻은 키값)&apiCode=ProductSearch&keyword=" +temp,
            data: {   key: "(얻은 키값)",
            	        apiCode: "ProductSearch",
            	        Keyword: temp,
            	        pageNum: "Default 1"
            	        	},
                        crossOrigin : true,
            headers : {openapikey: "(얻은 키값)"},
       
        success:function(data){ //성공적으로 불러왔을때 할일 
$(data).find("Product").each(function(){ 
var personInfo = "ProductCode : " + $(this).find("ProductCode").text() + "</br>" 
+ "ProductName : " +$(this).find("ProductName").text() + "</br>"
+ "<img src='" +$(this).find("ProductImage").text() + "'/>"+"</br>"; 
$('#target').append(personInfo)
temp=null; 
}) 
},
 error:function(){ //불러오지 못했을때 할일 
alert('Error loading XML document'); 
} 
}) 
}) 

}

    </script>
    <div id="target"></div>
</body>
</html>
