# \<h1\> ~ \<h6\> 문법

### 방법

```text
# stageus
## stageus
### stageus
#### stageus
##### stageus
###### stageus
```

### 결과

# stageus
## stageus
### stageus
#### stageus
##### stageus
###### stageus
  
------------------------------------------------------

# \<b\> \<i\> \<del\> \<ins\> 문법

### 방법

```text
볼드체 : **볼드체** 입니다.  
이텔릭체 : *이텔릭체* 입니다.  
취소선 : ~~취소선~~ 입니다.
```

### 결과

볼드체 : **볼드체** 입니다.  
이텔릭체 : *이텔릭체* 입니다.  
취소선 : ~~취소선~~ 입니다.  

------------------------------------------------------

# \<a\> 문법

### 방법

```text
[네이버](https://www.naver.com)
```

### 결과

[네이버](https://www.naver.com)

------------------------------------------------------

# \<image\> 문법

### 방법

```text
![이미지를 찾을 수 없습니다.](https://img1.daumcdn.net/thumb/R720x0.q80/?scode=mtistory2&fname=http%3A%2F%2Fcfile7.uf.tistory.com%2Fimage%2F24283C3858F778CA2EFABE)
```

※ Repository 내 이미지도 사용 가능

### 결과

![이미지를 찾을 수 없습니다.](https://img1.daumcdn.net/thumb/R720x0.q80/?scode=mtistory2&fname=http%3A%2F%2Fcfile7.uf.tistory.com%2Fimage%2F24283C3858F778CA2EFABE)

------------------------------------------------------

# \<code\> 문법

### 방법

#### 문법 앞 뒤로 어퍼스트로피(\`\`\`) 3개를 붙여줘야 함
```text 
print("Add Calculator")
a = 10
b = 20
print(a+b)
```

### 결과

```python
print("Add Calculator")
a = 10
b = 20
print(a+b)
```

### 방법

#### 문법 앞 뒤로 어퍼스트로피(\`\`\`) 3개를 붙여줘야 함
```text
<div>
  <h1>title</h1>
  <div>
    <p>contents 1</p>
    <p>contents 2</p>
  </div>
</div>
```

### 결과

```html
<div>
  <h1>title</h1>
  <div>
    <p>contents 1</p>
    <p>contents 2</p>
  </div>
</div>
```

------------------------------------------------------

# \<table\> \<td\> \<tr\> 문법

#### \[ User Table \]

### 방법

```text
|번호|이름|아이디|비밀번호|
|----|----|:---:|------:|
|1|스테이지|stageus|123456789|
|2|어스|admin!2☆|1234|
```

### 결과

|번호|이름|아이디|비밀번호|
|----|----|:---:|------:|
|1|스테이지|stageus|123456789|
|2|어스|admin!2☆|1234|

#### 기여자 목록

### 방법

```text
|이름|이메일|
|----|------|
|스테이지|stage@gmail.com|
|어스|us.gmail.com|
```

### 결과

|이름|이메일|
|----|------|
|스테이지|stage@gmail.com|
|어스|us.gmail.com|
