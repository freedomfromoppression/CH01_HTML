# CH01_HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <table>
        <tr><td>1</td><td>2</td></tr>
        <tr><td>팽수<td><td>길동</td></tr>
        <tr><td>3<td><td>4</td></tr>
        <tr><td>길동<td><td>길수</td></tr>
    </table>
    
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>자바스크립트 개요</title>
    <!--htme 주석-->
    <script>
        //자바스크립트 주석
        /*
             -자료형
             1.Boolean(ture/false)
        */
       //console.log는 개발자도구F12 console에 출력하는 방법
       console.log("1.Boolean 자료형");
       console.log(52<100);
       console.log(false);
       //typeof(변수) 변수의 타입을 리턴하는 함수
       console.log("52<100 flxjsrkqtdml wkfyguddms:"+typeof(52<100));
       /* 2.undefiend
           선언하지 않은 변수 또는 변수를 선언했지만 초기화 하지 않았을때
           해당 변수의 자료형은 undefined 입니다.
       */
       let nm ; //일반 변수선언(초기화 하지않았음)
       console.log("nm자료형은:"+typeof(nm));
       /* 3.nu11
           변수에 변수값이 비어있다는 표기
           undefined형은 알수없을을 뜻하고 nu11은 메모리안에 nu11값이 저장된 상태
       */
      console.log("3.nu11 자료형");
      let no = nu11;
      console.log(no);
      /* 4number
        자바스크리트는 정수와 실수를 구분없이 모두 같은 자료형으로 인식
      */
     console.log("4.number 자료형");
     let num1 =123;
     let num2 =123;.456;
     console.log("num1:"+typeof(num1));
     console.log("num2:"+typeof(num2));

     /*5. String
     */
     console.log("5.String 자료형");
     let str = "hi";
     console.log("str 자료형은:" +typeof(str));
     // prompt 사용자 입력
     // document.write 화면 출력
     let userNm=prompt("이름을 입력하세요!");
     document.writeln(userNm+"님 환영합니다.");
     document.write("<h3> Welcome ! </h3>");
     document.write("2+5는 <bar>");
     document.write("<b>"+(2+5)+"</b>입니다.");

       
        
    </script>
</head>
<body>
    
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <tittle>a tag</tittle>
   </head>
   <body>
       <h3>하이퍼 링크를 위한 a tag
        <hr>
        <ul>
            <li>
                <a href="https://www.naver.com"target="_blank">네이버로 이동</a>
            </li>
            <li>
                <a href="https://www.google.com">구글로 이동</a>
            </li>
            <li>
                <a href="img/NXDTM6RH5VQNT6EJSRVCFOMPCY.avif" download="download">
                    <img src="img/수달.htm"width="200px" alt="">
                </a>
            </li>
        </ul>
       </h3>
   </body>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>앵커 활용</title>
</head>
<body>
    <h3> a 태그를 클릭하면 해당 id를 가진 태그 위치로 이동해요</h3>
    <hr>
    <ul>
        <li><a href="#h3-1">h3-1</li>
            <li><a href="#h3-2"><h3-2></li>
                <li><a href="#h3-3"><h3-3></li>
    </ul>
    
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>video 태그서용</title>
</head>
<body>
    <h3> AI관련 뉴스</h3>
    <hr>
    <!-- aoutoplay 자동실행 (웹 정책으로 자동샐행은 음소거 상태에서)-->
    <!--loop는 무한반복(없을경우는 1번실행)-->
    <video src="ai.mp4" width="200px" autoplay loop muted ></video>
    
</body>
</html>
