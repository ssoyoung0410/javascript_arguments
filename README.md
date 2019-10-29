# javascript_arguments
arguments객체
함수라면 처음부터 가지고 있는 숨겨진 속성.


유사배열 형태로 배열의 메소드 (forEach,concat등등 사용불가)

배열의 메소드 사용하기위해서 ? call , apply 를 사용!
ex) Array.prototype.slice.call(arguments);
배열의 프로토타입에 있는 slice 함수를 빌려쓰고 ,
this 는 call을 사용하여 arguments를 가리키게 함.

