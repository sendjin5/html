# HTML 학습하기

##문서의 구성

html 문서는 DTD를 선언하고, html 태그를 열고, 그 안에 head와 body로 구분하여 작성한다.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!-- ol>li*7>a{목록&} -->
    <h2>순서형항목</h2>
    <ol>
        <li><a href="">목록1</a></li>
        <li><a href="">목록2</a></li>
        <li><a href="">목록3</a></li>
        <li><a href="">목록4</a></li>
        <li><a href="">목록5</a></li>
        <li><a href="">목록6</a></li>
        <li><a href="">목록7</a></li>
    </ol>
    <hr>
    <!-- ul>li*6>a{비순형 목록&} -->
    <h2>비순서형 목록</h2>
    <ul>
        <li><a href="">비순형 목록</a></li>
        <li><a href="">비순형 목록</a></li>
        <li><a href="">비순형 목록</a></li>
        <li><a href="">비순형 목록</a></li>
        <li><a href="">비순형 목록</a></li>
        <li><a href="">비순형 목록</a></li>
    </ul>
    <br>
    <dl><li><a href="">목록&</a></li>
    <li><a href="">목록&</a></li>
    <li><a href="">목록&</a></li>
    <li><a href="">목록&</a></li>
    <li><a href="">목록&</a></li>
    </dl>e
</body>
</html>
```