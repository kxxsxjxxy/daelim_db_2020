##1. for문을 사용하여 보기 내용을 출력하는 코드를 작성하시오
```
< 보기 >----
0 대림대학교
1 대림대학교
2 대림대학교
3 대림대학교
4 대림대학교
------------

답 :
for ($i = 0; $i < 5; $i++) {
    echo $i . " 대림대학교 <br>";
}
```

##2. 해당 변수가 배열인지 확인하는 함수는?
```
1. is_array()
2. foreach()
3. while()

답: 1번 (is_array() 의 매개값으로 전달된 변수가 배열일 경우 true | 배열이 아닌경우 false를 반환해준다.)
```

##3. while(괄호안에 들어갈 수 없는것은?)
```
1. $i = 0; $i < 5; $i++ 
2. is_array($arrays) // 해당 변수가 배열인지 확인하는 함수
3. strlen($arrays) // 문자열의 길이를 구하는 함수

답: 1번 (while 문의 조건제어값은 논리값만 사용 가능하기 때문)
```