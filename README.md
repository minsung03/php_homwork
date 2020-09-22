# php_homwork

## 민성_PHP_Today_Review

### 난이도 : ★★★★★★★★★★

```php
  <!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>얼굴책</title>
</head>
<body>
    <?php
        $str = "";
    ?>
    <a href="/login.php">로그인</a>
</body>
</html>
```

```login.php
  <?php
     $id = [];
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<form method="post" action="/index.php">
    <label for="id">아이디 : </label>
    <input type="email" placeholder="아이디를 입력하세요." name="login" required />

    <label for="pwd">비밀번호 : </label>
    <input type="text" placeholder="비밀번호를 입력하세요" name="pwd" required />
    <div class="button">
        <button type="submit">로그인</button>
    </div>
    </form>
</body>
</html>
```
