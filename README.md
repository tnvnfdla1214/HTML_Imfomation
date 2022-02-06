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







