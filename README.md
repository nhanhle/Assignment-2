Assignment-2
============
<!doctype html>
<html>
	<head>
			<title>La Lot Restaurant & Bar</title>
			<meta charset ="utf8">
	</head>
<body>

This space intentionally left blank.

<script>
var food = confirm('Do you prefer vietnamese soup (such as pho) or 
								vietnamese dry food (such as fried rice)?');
if (food) {
	var SoupOrDry = prompt('soup or dry?');
	SoupOrDry = SoupOrDry.toLowerCase();
	/*if (SoupOrDry == 'soup' || 
		SoupOrDry == 'soup food' || 
		SoupOrDry == 'vietnamese soup' ||
		SoupOrDry == 'vietnamese soup food') {
	console.log('Very fat pony');
	} else if (SoupOrDry == 'dry' ||
		SoupOrDry == 'dry food' ||
		SoupOrDry == 'vietnamese dry food') {
	console.log('Marmoset');
	} else {
	console.log('Chinchilla');
	}*/
	switch (SoupOrDry) {
		case 'soup':
		case 'soup food':
		case 'vietnamese soup' :
		case 'vietnamese soup food':
			console.log('Very fat pony');
			break;
		case 'dry':
		case 'dry food':
		case 'vietnamese dry food':
			console.log('Marmoset');
			break;
		default:
			console.log('Chinchilla');
			break;
	}
} else {
	var foods = prompt("How many kinds of vietnamese food have you tried?");
	foods = Number(foods);
	if (foods >=5) {
		console.log("Thankyou for loving vietnamese food.");
	} else {
		console.log("safdsag");
	}
	
}

</script>
</body>
</html>

 
