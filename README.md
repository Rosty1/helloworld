<html><body><pre><script>

//ejercicio 5 nivel 3


for (i=1;i<=50;i++){
	for (j=1;j<=i;j++){
		for (k=1;k<=i;k++){
			document.write("|");
			if (k!=i)
				document.write("<br>");
		}
		for (l=1;l<=j;l++){
			document.write("_ ");
			if (l==j)
				document.write("<br>");
		}document.write("<br>");
	}
}
</script></pre></body></html>
