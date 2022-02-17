TechOS 0.1 ( é mais um computador de bordo mas neh se tem imput de usuario e output pode ser considerado um OS) TechOS 0.1 é um script para organizar 
e mostar informaçoes da nave 
( qualquer info que seje computavel usando yolol) que pode ser des de erros na nave a quantidade de combustivel ou tempo de voo restante.

Na versão atual temos quatro telas, sendo uma de "load" puramente estético, uma tela de bem vindo duas de informaçoes da nave.

o fundamental pra funcionar: pag é um indexador interno. cpag é um indexador interno. :pp e :pm são os botoes que trocam de pagina 
( usei o botão simples no projeto) :b é o botão de boot ou restart que precionando vai reiniciar o sistema como um todo e voltando 
pra tela inicial :__ é o painel de texto usado pra mostrar os textos e infos

Módulos: informaçoes da naves devem ser formatadas dentro de cada loop de cada pagina por exemplo na linha 4 temos p=:gas/:gm*100
que é usado pra calcular a percentagem restante de propelente da nave. e na linha 5 temos o "print" das infos formatadas na linha acima.
