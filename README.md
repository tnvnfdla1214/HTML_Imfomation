# HTML_Imfomation

## 목차


## 1강
### h1,p,br,a,b,i,sup,ins,del 태그

<div align="center">
<img src = "https://user-images.githubusercontent.com/48902047/152688617-595e317c-a4d0-4e09-95aa-7fcc74ea1f84.png">
</div>

+ h1~h5 : 제목등에 쓰임 (글씨의 크기도 달라짐)
+ p : 문단
+ br : 띄어쓰기
+ a : a href="주소" 링크를 걸때 쓰임
+ b : bold체로 쓰임
+ i : 기울림
+ sup : 크기를 작게
+ ins : 밑줄
+ del : 글씨에 밑줄을 쳐 삭제 표현에 사용

## 2강
### 리스트 태그 - ul,li,ol

<div align="center">
<img src = "https://user-images.githubusercontent.com/48902047/152688877-8efc3a32-9c74-4306-9c58-4bf233d9e842.png">
</div>

위와 같이 사용됩니다.

### 리스트 태그 - dl,dt,dd

<div align="center">
<img src = "https://user-images.githubusercontent.com/48902047/152688953-b3974d1b-5071-4809-bd8e-39ea1bebcf81.png">
</div>

위와 같이 사용됩니다.

### 표를 나타내는 태그 - table

<div align="center">
<img src = "https://user-images.githubusercontent.com/48902047/152689028-9ddbdd69-217a-48ef-a95d-528581ead896.png">
</div>

1. table 태그로 감쌉니다. border은 행을 나타내는 두께입니다.
2. tr 태그는 하나의 행을 나타냅니다. rowspan 은 행을 합칩니다.
3. tr 태그 안의 td는 열을 나타냅니다.
4. tr 의 colspan 은 열을 합쳐줍니다.

### 이미지를 나타내는 태그 - img

<div align="center">
<img src = "https://user-images.githubusercontent.com/48902047/152689346-93f819d4-d95b-45e8-99f6-5b20987b5971.png">
</div>

+ 첫번쨰 예시는 해당 파일의 같은 디렉토리에 해당하는 이미지가 있을경우 이름으로 불러옵니다.
+ 두번쨰 예시는 링크를 통해 불러옵니다.
+ 네번쨰 예시의 width 은 크기를 나타냅니다.

### 사운드를 출력하는 태그 - audio

<div align="center">
<img src = "https://user-images.githubusercontent.com/48902047/152689557-b45fc220-c399-4a39-88ad-71ad017854cc.png">
</div>

+ controls : 플레이 버튼이나 정지 버튼과 같이 오디오의 실행을 제어할 수 있는 제어기가 표시됨을 명시함.
+ autoplay : 오디오가 실행될 준비가 끝나는 대로 자동으로 실행됨을 명시함.
+ loop : 오디오의 재생이 끝나면 자동으로 또다시 재생됨을 명시함.

## 주간 히트송 예제

<div align="center">
<img src = "https://user-images.githubusercontent.com/48902047/152689921-4ffa97ab-b23c-430a-91bd-e197c0c71716.png">
</div>

```HTML
<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <title></title>
</head>
<body>
    <table width="300" border="1">
        <tr>
            <td>
                <h1>주간 히트 노래</h1>
                <hr />
                <ol>
                    <li><img src="img01.png" alt="어머니 누구니"><a href="#">어머니 누구니</a></li>
                    <li><img src="img02.png" alt="한번 더 말해줘"><a href="#">한번 더 말해줘</a></li>
                    <li><img src="img03.png" alt="다른 남자 말고 너"><a href="#">다른 남자 말고 너</a></li>
                    <li><img src="img04.png" alt="모두가 내 발아래"><a href="#">모두가 내 발아래</a></li>
                    <li><img src="img05.png" alt="조만간 봐요"><a href="#">조만간 봐요</a></li>
                </ol>
                <p><audio src="34ex1.mp3" controls="controls" autoplay="autoplay"></audio></p>
            </td>
        </tr>
    </table>
</body>
</html>
```

## 3강
### 폼 태그
<div align="center">
<img src = "https://user-images.githubusercontent.com/48902047/152690388-32c788fb-1ac6-4d96-a8e5-acea0624ec1b.png">
</div>

1. form 태그로 묶어줍니다. 또한 action 뒤에 '#' 에는 주소를 정해주어 제출이란 버튼을 클릭시 해당하는 주소로 form 안의 정보들을 넘겨주게 됩니다. 그 다음 methed 는 보내는 방식을 선택하게 됩니다. 해당 예제는 get 방식이고 post 방식도 있습니다.(암호화의 차이)
2. input 태그는 기본적으로 type이란 속성과 name 이란 속성을 가지게 됩니다. type은 text,password 등 을 가지게 되며 name은 유니크한 이름입니다. 나중에 서버로 갔을때 연결할 때 사용됩니다.
3. 뿐만아니라 input 태그에는 size란 속성은 폭을 나타냅니다.
4. textarea는 길게 입력할때 쓰입니다. 속성으로는 row와 col이 있는데 높이와 너비를 나타냅니다.
5. select 태그는 안에 option이란 태그를 가지고 있습니다. 해당하는 option을 선택하게 됩니다. 속성으로는 multiple이란 속성으로 다중 선택이 가능하게 합니다.
6. 버튼의 타입은 submit이란 이름으로 정해줍니다.

<div align="center">
<img src = "https://user-images.githubusercontent.com/48902047/152725444-b7faf951-7937-4987-8a67-ee655813c41c.png">
</div>

1. div 태그는 블록을 쌓듯이 개행이 없지만 하나씩 순차적으로 나옵니다.
2. span 태그는 행이 바뀌어도 옆에 계속 나옵니다.

## 4강
### div를 이용한 레이아웃
<div align="center">
<img src = "https://user-images.githubusercontent.com/48902047/152725930-171edce5-0396-416c-ac15-77d46aad8f67.png">
</div>

위에서 학습하였던 table 태그는 많은 문제점을 가지고 있습니다. 현재에는 div 태그를 사용하고 있습니다.

div 태그는 블록을 쌓듯이 하나의 블록에 원하는 정보를 묶에 사용하면 됩니다.

### 시멘틱을 이용한 레이아웃
<div align="center">
<img src = "https://user-images.githubusercontent.com/48902047/152726410-54bdacc9-dfec-4b7c-b4df-d95cd1a53803.png">
</div>
시멘틱 태그는 div와 같은 기능을 갖습니다. 하지만 검색을 할때 좀더 빨리 검색엔진을 위해 header,nav,section,footer로 나누어 좀더 빨리 찾을 수 있게 해줍니다.
