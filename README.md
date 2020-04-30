<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="ru">
	<head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
        <style>
            .text {
             text-align:  center;
             font-family: Verdana, Arial, Helvetica, sans-serif; 
             font-size: 80%;
            }
			.form-group {
				width: 300px;
				margin-left: auto;
    			margin-right: auto;
			}
			</style>
		<title>Заявка</title>
	</head>

	<body>
        <div class="text">
		    <h2>Отправка заявки на конференцию</h2>
		    <h3>Основные данные</h3>
			<form>
				
				<div class="form-group">
					<label for="exampleInputName"><h4>*Фиамилия, имя, отчество:</h4></label>
					<input type="text" class="form-control" id="exampleInputName" placeholder="ФИО"> 
				</div>
				<h4>Пол:</h4>
		    	<p><input type="radio" name="с" />муж</p>
		    	<p><input type="radio" name="с" />жен</p>
				<div class="form-group">
					<label for="exampleInputData"><h4>Дата рождения:</h4></label>
					<input type="text" class="form-control" id="exampleInputData" placeholder="дд.мм.гггг"> 
				</div>
				<h3>Данные для создания личного кабинета</h3>
				<div class="form-group">
				  <label for="exampleInputEmail1"><h4>*Адрес электронной почты:</h4></label>
				  <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email"> 
				</div>
				<div class="form-group">
				  <label for="exampleInputPassword1"><h4>*Пароль для создания личного кабинета:</h4></label>
				  <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
				</div>
				<div class="form-group">
					<label for="exampleInputPassword2"><h4>*Подтверждение пароля:</h4></label>
					<input type="password" class="form-control" id="exampleInputPassword2" placeholder="PasswordRepeat">
				  </div>
				
			</form>
					
		    <h3>Материалы для конференции</h3>
		    <h4>*Тема доклада:</h4>
		    <p><input type="text" name="Тема" size="50" /></p>
		    <h4>*Тезисы доклада(не более 1000 символов):</h4>
		    <p><textarea rows="10" cols="45" name="text"></textarea></p>
		    <h4>*Файл презентации:</h4>
		    <p><input type="file" name="file" class="btn btn-primary" /></p>
		    <h3>Дополнительные сведения</h3>
		    <p><input type="checkbox" name="Проживание в отеле" /></p>
		    <p><label>Проживание в отеле</label></p>
		    <p><input checked="checked" type="checkbox" name="Завтрак" /></p>
		    <p><label>Завтрак</label></p>
		    <p><input type="checkbox" name="Обед" /></p>
		    <p><label>Обед</label></p>
		    <p><input type="checkbox" name="Ужин" /></p>
		    <p><label>Ужин</label></p>
		    <hr />
			<p><input type="submit" name="submit" class="btn btn-success" onclick="myFunction()" /></p>
			<script>
				function myFunction() {
				  alert(`что получилось:`+`\nзвать тебя - `+ document.getElementById("exampleInputName").value + `\nродился ты - `+ document.getElementById("exampleInputData").value + `\nпочта твоя - `+ document.getElementById("exampleInputEmail1").value + `\nсобирай чемоданы, прикатывай` );
				}
				</script>
		    <hr />
            <h6>*Поля отмеченные звездочкой являются обязательными для заполнения</h6>
        </div>
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
	</body>
</html> 
