# tabs

Tab과 몇가지 키워드로 좀 더 사용을 편리하게 만드는 Lisp의 방언입니다.

JavaScript 환경에서 동작합니다.

### 예제
```
func square x
	return * x x

console.log(square 5)

func cube x
	return * x (square x)
	
console.log(cube 5)

func fill container liquid
	if == liquid nil
		var liquid 'coffee'
	return + 'Filling the ' container ' with ' liquid '...'

console.log(fill 'a')

var song (array 1 2 3 4 5)

console.log song

var i 0
while != i 5
	console.log i
	= i (+ i 1)
```