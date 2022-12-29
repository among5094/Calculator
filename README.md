# Rainbow Calculator🌈

현재 모습(이미지는 계속 업데이트 할 예정...)

<!--
영상
https://user-images.githubusercontent.com/106166621/209961887-7e50c2b2-3ed5-449a-b179-a1a33ced14c8.mp4

-->

![화면 캡처 2022-12-29 220142](https://user-images.githubusercontent.com/106166621/209954735-3a1a089b-ec11-467d-9474-33ae4bdc3d49.png)


<br><br>
기본적인 계산을 할 수 있는 무지개 계산기 입니다! <br>
HTML과 CSS를 사용해보았습니다.
최종 목표는 이 계산기를 어플로 내보는 것입니다. <br>


<img src="https://user-images.githubusercontent.com/106166621/209563554-fd499c4d-6039-4722-b0db-d6dc9b7a2fb2.png" width="400" height="450"> <br>


우선 유튜브로 기본적인 계산기 만드는 법을 보고 제 입맛대로 색상과 디자인을 추가했습니다. <br>
이 상태로만 두기에는 심심해서 움직이는 글씨를 넣어보았습니다.  <br><br>

**그런데 중간에 문제가 생겼습니다**

<img src= https://user-images.githubusercontent.com/106166621/209953331-d2f715fe-48c2-452e-baa7-09de7f86a35f.png width="900" height="300"> <br>

body 안에 display: flex 를 해주었습니다 <br>
body안에 공간을 나눠주다보니 h1로 글자를 넣어주니까 글자가 가운데로 가는 ~~문제~~가 생겼습니다. 아래 사진처럼요ㅠㅠ😂 <br>

<img src= https://user-images.githubusercontent.com/106166621/209953680-79c73a69-2b2f-4146-b92e-c5f09e7975ae.png width="700" height="300"> <br>

<br> <!--문제  -->
그래서 body에 flex-direction: column; 코드를 추가해서 문제를 해결했습니다 <br>
이 코드의 뜻은 공간을 나눌 방향을 (flex-direction)을 세로로 쌓아주듯이 나눈다는 의미입니다 <br>

![화면 캡처 2022-12-29 220142](https://user-images.githubusercontent.com/106166621/209954735-3a1a089b-ec11-467d-9474-33ae4bdc3d49.png)

이렇게 올바르게 글자가 올라간 모습입니다😊 <br><br><br><br>


