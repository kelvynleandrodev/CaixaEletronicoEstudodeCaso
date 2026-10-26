# Caixa-Eletronico---Estudo-de-caso

Cenário
Uma cooperativa de crédito está criando um simulador de caixa eletrônico para treinamento. O programa
começa com saldo de R$ 1.000,00 e deve permitir que a pessoa consulte o saldo, faça um saque ou
encerre o atendimento. Durante os testes, a equipe percebeu que algumas entradas derrubam o
programa e outras permitem valores que não deveriam ser aceitos. Seu grupo foi solicitado a corrigir o
comportamento.
O que o programa deverá fazer
★ O saldo inicial deve ser R$ 1.000,00.
★ O menu deve oferecer: 1 Consultar saldo; 2 Sacar; 3 Sair.
★ Se a pessoa digitar letras quando o programa espera uma opção numérica ou um valor de saque, o
programa deve apresentar uma mensagem clara e continuar funcionando.
★ O valor do saque precisa ser maior que zero.
★ O saque não pode ultrapassar o saldo disponível.
★ Se o saque for válido, o saldo deve ser atualizado e o novo saldo exibido.
★ Uma opção de menu inexistente deve ser recusada sem encerrar inesperadamente o programa.
★ O menu deve continuar aparecendo até a pessoa escolher sair.

Criar uma exceção personalizada chamada SaldoInsuficienteError e utilizá-la quando o saque solicitado
for maior que o saldo.
