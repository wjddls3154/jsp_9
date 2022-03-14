# jsp_9 : 배열

![image](https://user-images.githubusercontent.com/37132897/158111355-01ca79fe-bbe1-49ab-87e3-6af501e1e45b.png)

      // 배열 선언 
      
      var Arr = [10, 20, 30, 40, 50];
      
      // 배열 이용 예제
      
      document.write(Arr[0]); // 1. 인덱스 0, (10) 출력, 인덱스는 0부터 시작
      
      document.write("<br>");      
      
      document.write(Arr[1]); // 2. 인덱스 1, (20) 출력      
      
      document.write("<br>");      
      
      document.write(Arr.slice(0, 3)); // 3. 0번째부터 3번째 전(2번째) 까지 출력하겠다.      
      
      document.write("<br>");      
      
      document.write(Arr.pop()); // 4. 50을 빼냄      
      
      document.write("<br>");      
      
      document.write(Arr); // 5. 제일 뒤에 있는 50이 빠지고, 10 20 30 40 만 존재      
      
      document.write("<br>");      
      
      Arr.push(1000); // * 1000을 집어넣는다.      
      
      document.write(Arr); // 6. 10 20 30 40 1000 으로, 마지막에 1000이 들어갔다.      
      
      document.write("<br>");      
      
      document.write(Arr.join("!!"));      
      
      document.write("<br>"); // 7. 10!!20!!30!!40!!1000 으로, 사이사이에 '!!'가 들어간걸 확인할 수 있고 string 으로 반환되었다.      
      
      Arr.sort(); // 8. 사전식 정렬 : 10 1000 20 30 40 으로 정렬되는데, 그 이유가 앞의 글자 1,2,3,4만 보고 사전식으로 정렬한것      
      
      document.write(Arr);      
      
      document.write("<br>");      
      
      Arr.reverse(); // 9. 사전식 정렬을 역순으로 바꿔주는 것 : 40,30,20,1000,10 으로      
      
      document.write(Arr);      
      
      document.write("<br>");
      
      
