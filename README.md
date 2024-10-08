<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>폼태그</title>
</head>
<body>
<!--   method는 get과 post를 사용할 수 있음
   get : 위에 창에 보낸 정보가 표시됨(아무 입력 안할시 get이 디폴트)
   post : 위에 창에 보낸 정보가 표시되지 않고 다른 방식으로 전송-->
    <form action="#" method="get">
    <!--action은 이동할 페이지를 지정을 하는것-->
    
    
    
    <h1>회원가입 진행</h1>
    <b><hr></b>
   <h3>개인 정보 입력</h3> 

    <!--사용자가 입력하는 입력 양식-->
    <!--name은 이동한 페이지에서 참조하는 값-->
    이름 <input type="text" name="text" value ="이름을 입력하시오." > <br>
    
    
    성별
    <!--radio속성은 오로지 한 개만 선택할 수 있도록 반드시 name을 동일하게 해야한다.-->
    <!--value는 이동한 페이지에서 참조하는 실제 값-->
    남<input type = "radio" name = "gender" value ="man">   
    여<input type="radio" name = "gender" value = "woman"> 
    <br>
    <br><hr>
    
    
    <h3>아이디&amp;패스워드 입력</h3>
    아이디 <input type="text" name="text" >  <br>
    비밀번호 <input type="password" name="password" >
        
    <br><br><hr>
    <h3>취미 입력</h3>
    
    <!--checkbox는 다중선택이 가능한 입력양식이며, 반드시 name이 동일해야한다.
    value값은 이동한 페이지에서 참조하는 실제값--> 
    독서<input type="checkbox" name = "hobby" value="reading"/>    
    운동<input type="checkbox" name = "hobby" value = "health"/>    
    스포츠활동<input type="checkbox" name = "hobby" value= "sports"/>   
    맛집탐방<input type="checkbox" name = "hobby" value="foodStore"/>   
    영화관람<input type="checkbox" name = "hobby" value = "movie"/>   
    TV&amp;OTT시청<input type="checkbox" name = "hobby" value = "tv_ott"/>   
    산책<input type="checkbox" name = "hobby" value = "walking"/>
    요리<input type="checkbox" name = "hobby" value = "cooking"/>        
          
    <br><br><hr>
    <h3>본인 사진 첨부</h3>  
    파일 첨부<input type="file" name = "file" value = "자기소개서">
    
    
    <!--보통 접속일시, 회원가입 일시 등과 같이 사용자에게 보일 필요가 없는 정보를 전달할 때 사용함-->
    <input type="hidden" name = "hidden" value = "clock">
    
    
    <br><br><hr>
    <h3>버튼</h3>  
    <input type="button" value = "버튼">
    <input type="reset" value = "입력한 정보 초기화">
    <input type="submit" value="회원가입"> <br>
               
    <br><br><hr>
    <h3>수고하셨습니다.</h3>           
    <input type="image" src = "https://search.pstatic.net/sunny/?src=https%3A%2F%2Fwww.smu.ac.kr%2F_attach%2Fimage%2F2022%2F10%2FPLKqTefaQxGfcnMdjloJ">
                  
    </form>
    
    
    
    
    
</body>
</html>
