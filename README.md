<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title></title>
	</head>
	<body>

		<script>
			 for(var i =0;i<4;i++){
			        for(var j = 0;j<3-i;j++){
			            document.write('&ensp;')
			        }
			        for(var k = 0;k<2*i+1;k++){
			            document.write('*')
			        }
			        document.write('<br>')
			    }
			for(var b=1;b<=3;b++)
			{
				for(var y=1;y<=b;y++)
				{
					document.write('&ensp;')
				}
				for(var x=0;x<=6-b*2;x++)
				{
					document.write('*');
				}document.write('<br>')
			}
			
	</script>
	</body>
</html>
