# Anton Sharafiev

##### Junior Frontend Developer

---

##### Contact information:

**E-mail:** a.sharafiev@gmail.com  
**Phone:** +2 015-554-96485  
**Facebook:** [Tonic benetonic](https://www.facebook.com/tonic.benetonic/)  
**Area:** Russia, Moscow, marshala Novikova street, 11 - 2

---

##### About me:

I am a responsible, reliable, punctual and self-organized person. I have a technical mindset, higher engineering education. I am good at learning new areas, I have experience in various positions. I have excellent communication skills, I can work in a team, I can manage a project. In my work, I use an integrated approach to solving tasks, and I believe that any goal is achievable. I am one of those who are not afraid of difficulties. I know how to find an approach to people, I know how to motivate myself and others. I am constantly engaged in self-education and value the time of both my own and my colleagues and partners. In people I appreciate honesty, openness, decency and good intentions.

---

##### My skills:

- Github Basics
- VS Code, Sublime Text Basics
- HTML, CSS Basics
- PHP Basics
- JavaScript Basics
- Android Studio Basics
- SEO Basics

---

##### Code example:

```
<?php
session_start(); # стартуем сессию
?>

<!DOCTYPE html>
<html>
<head>
	<title>IQ NINJA</title>
	<link rel="stylesheet" type="text/css" href="index_style.css">
</head>
<body id="index_body">

		<h1 align="center">IQ NINJA</h1>
		<div id=block_for_message align="center" class="simpleText">  <!--div для вывода сообщения об ошибке-->
	<? if (isset($_SESSION["error_messages"]) && !empty($_SESSION["error_messages"])){
		echo $_SESSION["error_messages"];
		unset($_SESSION["error_messages"]);
	}
	?>
</div>
<div id=start_battle>
	<form action="login.php" method="post"> <!--файл login.php это обработчик формы-->
		Login <input id="login" type="text" name="login" required="required" maxlength="25"><br />
		<br />
		Password <input id="password" type="password" name="password" required="required" maxlength="32"><br /><br />
		<input type="submit" name="auth_button" value="Вход" /><br /><br />
	</form>
		<input type="button" name="GO" value="Регистрация" onclick='location.href="reg.php"' />

</div>


</body>
</html>
```

---

##### Courses:

- Introduction to SEO in 30 days, Devaka (completed)
- RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

---

##### Languages:

- English - A2
- Russian - Native
