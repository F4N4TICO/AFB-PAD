# AFB-PAD

PROFESSOR ESSA PROVA FOI MUITO COMPLICADA, FAZ UMA REVISÃO PFVR 

var result = someFun({someProrpety: 'interview', function(value)

{
    console.log(`thisPosting to${value}`);
}})
 console.log ( "result is", result );
 function someFun ( teste, teste2){ teste2(teste.someProperty); return 1;}

 //questao 2
 var someFN = function(numero) 
    {
        var valor = numero;

        return function (incremento)
        {
            valor += incremento;
            return valor;
        }
    }

    var counter  = someFN(1)

    console.log("First call", counter(3))
    console.log("second call", counter(1))
    console.log("Third call", counter(5))

//questao 4

var a  = 5
var b = 10

if(a == 5){
  let a = 4
  var b = 1
  console.log(a)
  console.log(b)
}
console.log(a)
console.log(b)
//o resultado sera : 4,1,5,1

//questao 5

function num(numero)
{
  for(var i = 1; i <= 10; ++i)
  {
    console.log(i * numero)
    
  }
}
num(2)
