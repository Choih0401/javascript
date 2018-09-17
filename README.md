# **출력**

 document.write("Hello World!");


# **주석**

//한 줄 주석

/* 여러줄

주석

*/


# **변수 (String, Number, Boolean, NULL)**
```javascript
var message;
message = "Hello World";

var num = Number("7"); -> 문자열 데이터에서 숫자열 데이터로 바뀜

var bool=true; -> 논리형 데이터(true or false)

//typeof -> 데이터형 추출
var num = 10;
document.write(typeof num); -> number 출력
```

# **비교연산자**
```javascript
var a = 10;
var b = "10";

document.write(a==b); // true -> 데이터형과 무관하게 표기된 숫자만 비교

document.write(a===b); // false -> 데이터형도 반영하여 비교
```

# **제어문**
```javascript
if(조건식){
	실행문;	
}else if(조선식){
	실행문;
}

switch(변수){
	case 값 1:	
	break;	
}

while(조선식){
	실행문;	
	증감식;	
}

do{
	실행문;	
	증감식;	
}while(조건식)

for(초기값; 조건식; 증감식){
	실행문;
	
}
```

# **객체**
```javascript
Date 객체 -> new Date(), new Date(dateString) etc..

Date Get 메서드 -> getDate(), getDay etc..

Number 객체 -> MAX_VALUE, MIN_VALUE etc..

Nuber 객체 메서드 -> toFixed(n), toString etc..

etc....


# **함수**

fuction 함수명(){
	실행문;
	reuturn 데이터;
}

참조변수 = function(){
	실행문;
}

function 함수명(){(매개변수1, 매개변수2)
	실행문;
}
```
# **함수**
```javascript
function 함수명(){
	실행문;
	reuturn 데이터;
}

참조변수 = function(){
	실행문;
}

function 함수명(){(매개변수1, 매개변수2)
	실행문;
}
```
