#대구 AI 스쿨

Add file > Upload files 에서 파일을 업로드 할 경우.

'choose your files'를 해서 파일을 업로드 할 경우 폴더는 적용되지 않음

파일이랑 폴더를같이 드래그해서 업로드 해야지만 폴더도 같이 올라감

---------------------------------------------------------------------------

22/03/23

<javaScript>

html은 정적으로, 정보를 나타냄

css는 디자인

javaScript는 동적으로. 사용자와 상호작용 함

<syntax>
  
    <head>랑 <body>에 상관 없이 <script>를 사용하여 동작함
  
    document.write();를 사용하면 웹 브라우저에 괄호안의 내용이 표시
 
    ex) document.write(Math.random()); //웹 브라우저에 0과 1사이의 숫자가 랜덤으로 생성, 새로고침 할 때 마다 변경
  
    console.log();를 사용하면 개발자도구의 콘솔창에 괄호안의 내용이 표시
  
    ex) console.log(Math.PI); //콘솔창에 '3.141592653589793'가 표시
      
<data type>
  
  숫자
  
    정수 : 1

    실수 : 1.1
  
    연산자(operator) : + - * /
  
    floor : 소수점 버림
  
    ex) console.log(Mate.floor(1.9)); //콘솔창에 1이 표시
 
    함수 : 끝이 )로 끝나는 것 ex) rendom(), floor(), (1)
  
  문자열
    
    '와' 사이, "와" 사이에 원하는 문자를 입력
  
    단, '와 "를 섞어서 사용 불가능, 문장을 한줄에 다 적어야함
  
    여러 줄을 사용하고 싶을 때 :
      
      'Hello\
      rld' //코드 상에서만 줄바꿈
  
      `Hello
      World` //실제 나타내는 값에서도 줄바꿈
