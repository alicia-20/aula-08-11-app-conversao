# Aula 08-11 - App Conversão de moeda

## Avaliação

* Implemente para que o usuário possa fazer conversão de outras moedas (mínimo + 3 moedas);
* Descreva abaixo o seu entendimento acerca desta atividade, explorando as funcionalidades das classes que contruímos e os principais pontos da aplicação;

## Entrega

* Clone este repositório e faça o que se pede;
* Realize um commit das suas alterações no seu repositório;
* Envie o link do repositório na avaliação gerada no classroom;

## Descritivo do Aluno:

-> DESCREVA AQUI <-

O aplictivo desenvolve um retorno ao usuário de valor da moeda selecionada (nesse caso de real 
para Franco-moeda Suiça- e/ ou Yuan-moeda Chinesa-).
Ultilizamos a função "CurrencyRate" que tem como característica retornar a taxa de conversão 
para a moeda corporativa referente ao código ISO da moeda especificada.

Ademais, também foi utilizada a função "jsonObject.has" que possibilita visualizar o nome do membro
em referencia na consulta. Nesse caso, o sistema utilizado retorna ao usuario os códigos da moeda em questão 
unidos. 

Na linha 100 é apresentado o seguinte código: " TextView resultado = findViewById(R.id.resultado);" que implica o retorno do sistema refernete a solicitação realizada
pelo Usuario. Esse retorno trás ao contribuinte o resultado do pedido do valor em questão. 

Nas linhas 93/94 temos também um "else":  } else { Toast.makeText(getApplicationContext(), 
"Não foi possível encontrar o valor da moeda", Toast.LENGTH_SHORT).show(); que retorna ao usuário uma resposta de "não sert possível encontrar a moeda" pois 
o registro da moeda está restrito apenas em dois





 
