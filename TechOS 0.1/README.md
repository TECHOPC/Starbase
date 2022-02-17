TechOS 0.1 ( é um computador de bordo mas como tem imput de usuario e output dados, pode ser considerado um OS)<br />
TechOS 0.1 é um script para organizar e mostar informaçoes da nave ( qualquer info que seje computavel usando yolol) <br />
que pode ser des de erros na nave a quantidade de combustivel ou tempo de voo restante.<br />
<br />
<br />
Na versão atual temos quatro telas, sendo uma de "load" puramente estético, uma tela de bem vindo duas de informaçoes da nave.<br />
<br />
o fundamental pra funcionar:<br />
:pp e :pm são os botoes que trocam de pagina ( usei o botão simples no projeto)<br />
:b é o botão de boot ou restart que precionando vai reiniciar o sistema como um todo e voltando pra tela inicial<br />
:__ é o painel de texto usado pra mostrar os textos e infos<br />
<br />
Módulos: informaçoes da naves devem ser formatadas dentro de cada loop de cada pagina por exemplo na linha 4 temos p=:gas/:gm*100<br />
que é usado pra calcular a percentagem restante de propelente da nave. e na linha 5 temos o "print" das infos formatadas na linha acima.<br />
