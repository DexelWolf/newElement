# newElement
добавление нового html элемента( createElement\appendChild)
<!DOCTYPE html>
<html>
<head>
	<title>Новые элементы</title>
	<script type="text/javascript">
		function addItem(){
			var newItem = document.createElement("div");
			newItem.innerHTML = "Новый элемент";
			document.getElementById("list").appendChild (newItem);
		}
	</script>
</head>
<body>
	<div onclick="addItem();" id="list">Нажми, чтобы добавить элемент.
		
	</div>

</body>
</html>
