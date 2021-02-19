<!DOCTYPE html>
<html>
<head>
	<title>Metodos de raices</title>
<script>
MathJax = {
  loader: {load: ['input/asciimath', 'output/chtml']}
}
</script>
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/startup.js">
</script>


</head>
<body>
<style type="text/css">
	* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
	}

	body {
    background-image: linear-gradient(-225deg, #f6ff00 0%, #20e8de 100%);
	background-image: linear-gradient(to top, #f2e74e 0%, #a6fffb 100%);
	background-attachment: fixed;
  	background-repeat: no-repeat;
    font-family: 'Arial', 'Helvetica', sans-serif;
	opacity: .95;
	}

	form {
    width: 1200px;
    min-height: 500px;
    height: auto;
    border-radius: 5px;
    margin: 2% auto;
    box-shadow: 0 9px 50px hsla(20, 67%, 75%, 0.31);
    padding: 2%;
    background-image: linear-gradient(-225deg, #f6ff00 0%, #20e8de 100%);
	background-image: linear-gradient(to top, #f2e74e 0%, #a6fffb 100%);
	text-align: center;
	}


	form select{
	width: 500px;
    height: 50px;
    font-size: 80%;
    font-family: 'Arial', 'Helvetica', sans-serif;
    border-radius: 40px 40px 40px 40px;
    color: #5E6472;
	}

	form label{
		font-size: 150%;
    	font-family: 'Arial', 'Helvetica', sans-serif;
    	color: #1f52ed;
	}

	form label[class="parente"]{
		font-size: 250%;
    	font-family: 'Arial', 'Helvetica', sans-serif;
    	color: #1f52ed;
	}

	header {
    margin: 2% auto 2% auto;
    text-align: center;
	}
	header h2 {
    font-size: 250%;
    font-family: 'Arial', 'Helvetica', sans-serif;
    color: #1f52ed;
	}

	input[class="entradas_form"]{
    width: 50px;
    height: 40px;
  
    margin-top: 2%;
    padding: 5px;
    margin-bottom: 2%;
    
    font-size: 16px;
    font-family: 'Arial', 'Helvetica', sans-serif;
    color: #5E6472;
  
    outline: none;
    border: none;
  
    border-radius: 20px 20px 20px 20px;
    transition: 0.2s linear;
    
	}

	input[class="entradas_form1"]{
    width: 350px;
    height: 20px;
  
    margin-top: 1%;
    padding: 5px;
    margin-bottom: 1%;
    
    font-size: 16px;
    font-family: 'Arial', 'Helvetica', sans-serif;
    color: #5E6472;
  
    outline: none;
    border: none;
  
    border-radius: 20px 20px 20px 20px;
    transition: 0.2s linear;
    
	}


	button {
	font-size: 16px;
    font-family: 'Arial', 'Helvetica', sans-serif;
    color: #5E6472;

    display: inline-block;
    color: #ffffff;
  
    width: 200px;
    height: 50px;
  
    padding: 0 0;
    background: #0f48f5;
    border-radius: 40px 40px 40px 40px;
    
    outline: none;
    border: none;
  
    cursor: pointer;
    text-align: center;
    transition: all 0.2s linear;
    
    margin: 7% auto;
    letter-spacing: 0.05em;
	}


	</style>
<form action='' method='post'>
	<header>
		<h2>Metodo biseccion</h2>
	</header><br>
<form action='' method='post'>
	
 		<input class='entradas_form' type='number' step=any name='x10' value='0' required title='Ingrese un numero'>
		<label>`x^10`</label> &nbsp;&nbsp;&nbsp;&nbsp;
		<input class='entradas_form' type='number' step=any name='x9' value='0' required title='Ingrese un numero'>
		<label>`x^9`</label> &nbsp;&nbsp;&nbsp;&nbsp;
		<input class='entradas_form' type='number' step=any name='x8' value='0' required  title='Ingrese un numero'>
		<label>`x^8`</label> &nbsp;&nbsp;&nbsp;&nbsp;
		<input class='entradas_form' type='number' step=any name='x7' value='0' required  title='Ingrese un numero'>
		<label>`x^7`</label> &nbsp;&nbsp;&nbsp;&nbsp;
		<input class='entradas_form' type='number' step=any name='x6' value='0' required  title='Ingrese un numero'>
		<label>`x^6`</label> &nbsp;&nbsp;&nbsp;&nbsp;

		<input class='entradas_form' type='number' step=any name='x5' value='0' required  title='Ingrese un numero'>
		<label>`x^5`</label> &nbsp;&nbsp;&nbsp;&nbsp;
		<input class='entradas_form' type='number' step=any name='x4' value='0' required  title='Ingrese un numero'>
		<label>`x^4`</label> &nbsp;&nbsp;&nbsp;&nbsp;
		
		<input class='entradas_form' type='number' step=any name='x3' value='0' required  title='Ingrese un numero'>
		<label>`x^3`</label> &nbsp;&nbsp;&nbsp;&nbsp;
		
		<input class='entradas_form' type='number' step=any name='x2' value='0' required  title='Ingrese un numero'>
		<label>`x^2`</label> &nbsp;&nbsp;&nbsp;&nbsp;
		
		<input class='entradas_form' type='number' step=any name='x' value='0' required  title='Ingrese un numero'>
		<label>`x`</label> &nbsp;&nbsp;&nbsp;&nbsp;
		
		<input class='entradas_form' type='number' step=any name='x0' value='0' required title='Ingrese un numero'> &nbsp;&nbsp;&nbsp;&nbsp; <br>

		<label>`+`</label>
		<label class="parente">`(`</label>
		<input class='entradas_form' type='number' step=any name='euler' value='0' required title='Ingrese un numero'>
		<label>`e`</label>

		<label>`^`</label>
		<input class='entradas_form' type='number' step=any name='xeuler' value='0' required  title='Ingrese un numero'>
		<label class="parente">`)`</label>
		<label>`+`</label>
		
		<label class="parente">`(`</label>
		<input class='entradas_form' type='number' step=any name='as' value='0' required  title='Ingrese un numero'>
		<label>`sen(`</label>
		<input class='entradas_form' type='number' step=any name='bs' value='0' required  title='Ingrese un numero'>
		<label>`x)`</label>
		<label class="parente">`)`</label>
		<label>`+`</label>
		<label class="parente">`(`</label>
		<input class='entradas_form' type='number' step=any name='ac' value='0' required  title='Ingrese un numero'>
		<label>`cos(`</label>
		<input class='entradas_form' type='number' step=any name='bc' value='0' required  title='Ingrese un numero'>
		<label>`x)`</label>
		<label class="parente">`)`</label>
		<label>`=0`</label><br>

		<label>Valor a</label><br>
		<input class='entradas_form1' type='number' step=any name='a' placeholder='Ingresa el valor de a' required title='Ingrese un numero'><br>
		<label>Valor b</label><br>
		<input class='entradas_form1' type='number' step=any name='b' placeholder='Ingresa el valor de b' required><br>
		<label>Valor de Tolerancia</label><br>
		<input class='entradas_form1' type='number' step=any name='Tol' placeholder='Ingresa un valor de tolerancia' required><br>
		<label>Numero maximo de iteraciones</label><br>
		<input class='entradas_form1' type='number' step=any name='N' placeholder='Ingresa un numero maximo de iteraciones' required><br>

		<button type='submit' name='calcularpoli'>Calcular</button>
	









<?php




	function ecuacion1($valor,$x0,$x,$x2,$x3,$x4,$x5,$x6,$x7,$x8,$x9,$x10,$euler,$xeuler,$as,$bs,$ac,$bc){
		$r=$x0+($x*$valor)+($x2*($valor**2))+($x3*($valor**3))+($x4*($valor**4))+($x5*($valor**5))+($x6*($valor**6))+($x7*($valor**7))+($x8*($valor**8))+($x9*($valor**9))+($x10*($valor**10))+($euler*((M_E)**($xeuler*$valor)))+($as*sin($bs*$valor))+($ac*cos($bc*$valor));

    	return $r;
	}
if(isset($_POST['calcularpoli'])){
$x0=$_POST['x0'];
$x=$_POST['x'];
$x2=$_POST['x2'];
$x3=$_POST['x3'];
$x4=$_POST['x4'];
$x5=$_POST['x5'];
$x6=$_POST['x6'];
$x7=$_POST['x7'];
$x8=$_POST['x8'];
$x9=$_POST['x9'];
$x10=$_POST['x10'];
$euler=$_POST['euler'];
$xeuler=$_POST['xeuler'];
$as=$_POST['as'];
$bs=$_POST['bs'];
$ac=$_POST['ac'];
$bc=$_POST['bc'];

$array[10]=$x10;
$array[9]=$x9;
$array[8]=$x8;
$array[7]=$x7;
$array[6]=$x6;
$array[5]=$x5;
$array[4]=$x4;
$array[3]=$x3;
$array[2]=$x2;
$array[1]=$x;
$array[0]=$x0;
$array[11]=$euler;
$array[12]=$as;
$array[13]=$ac;

$a=$_POST['a'];
$b=$_POST['b'];
$Tol=$_POST['Tol'];
$N=$_POST['N'];
$i=1;
$FA=ecuacion1($a,$x0,$x,$x2,$x3,$x4,$x5,$x6,$x7,$x8,$x9,$x10,$euler,$xeuler,$as,$bs,$ac,$bc);

while ($i<=$N) {
	$p=$a+(($b-$a)/2);
	$FP=ecuacion1($p,$x0,$x,$x2,$x3,$x4,$x5,$x6,$x7,$x8,$x9,$x10,$euler,$xeuler,$as,$bs,$ac,$bc);

	if ($FP==0 or (($b-$a)/2)<=$Tol) {
		echo "<br> <label>La funcion calculada fue:<br> `";

		
		for ($lol=10; $lol >1 ; $lol--) { 
			if ($array[$lol]!=0) {
				echo $array[$lol]."*(x^$lol)";
			} else if ($array[$lol]==0) {
				echo "";
			}

		}

		if ($array[0]!=0) {
			echo $array[0];
		}

		echo "<br>";
		if ($array[11]!=0) {
			echo "$euler*(e^($xeuler*x))+";
		} else if ($array[12]!=0) {
			echo "$as*sin($bs*x)+";
		} else if ($array[13]!=0) {
			echo "$ac*cos($bc*x)";
		} else {
			echo "";
		}
		
		echo "=0`</label><br><br>";


		echo "<br> <label>Proceso terminado</label>";
		echo "<br> <label>La raiz es: $p </label>";
		echo "<br> <label>La raiz redondeada es:".round($p, 1, PHP_ROUND_HALF_ODD). "</label> <br>"; 
		echo " <label>El numero de iteraciones necesarias fue: $i</label>";
	
		exit;
	}
	if (($FA*$FP)>=0) {
		$a=$p;
		$FA=$FP;
	} else if (($FA*$FP)<0) {
		$b=$p;
	}
	
	$i++;

	if ($i==$N+1) {
		echo "<br> <label>Numero de iteraciones maximas alcanzado <br> El metodo fracaso despues de $N iteraciones</label>";
	}
}

}
echo "</form>";




 ?>


</form> 
</body>
</html>

