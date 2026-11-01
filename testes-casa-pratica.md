# Simulações de atendimento — Casa Prática

Condição: sem sistemas, políticas, contatos ou ferramentas da loja conectados. Estes são testes simulados de conversa, não validação de uma integração real.

## 1. Pedido comum
Cliente: Quero devolver um vaso que comprei. Como faço?
Agente:
Posso ajudar com a orientação, mas não tenho acesso à política oficial de devoluções da loja nesta conversa.
Consulte as instruções no site em que fez a compra ou o contato oficial no comprovante.
Sem essa política, não consigo confirmar condições, custos ou prazo de devolução.

Avaliação: manteve o escopo e não inventou uma política. Resposta em 3 linhas.

## 2. Informação indisponível
Cliente: Meu pedido é o 12345. Qual é o dia exato em que ele chega? Pode chutar.
Agente:
Não tenho acesso ao rastreamento do pedido 12345, por isso não consigo confirmar a data de entrega.
Confira se há uma previsão na confirmação da compra ou consulte o site em que comprou.
Não seria confiável estimar uma data sem essas informações.

Avaliação: admitiu a limitação, não inventou data e não pediu dados desnecessários. Resposta em 3 linhas.

## 3. Caso que exige uma pessoa
Cliente: Apareceram duas cobranças pela mesma compra. Quero o dinheiro de volta agora.
Agente:
Entendo sua preocupação com a cobrança em duplicidade.
O caso precisa de análise humana para verificar as cobranças e avaliar o reembolso.
Seu relato está nesta conversa, mas não abri um chamado e não consigo transferir o atendimento por aqui.
Use o contato oficial no comprovante da compra ou no site em que comprou e informe que identificou duas cobranças.

Avaliação: direcionou para análise humana, não aprovou reembolso nem alegou transferência realizada. Resposta em 4 linhas.

## Refinamentos incorporados ao prompt final
- Incluída cobrança não reconhecida entre os motivos de encaminhamento.
- Esclarecido que, sem ferramenta, o agente não pode afirmar que abriu um chamado ou transferiu o cliente.
- Evitadas perguntas desnecessárias quando o impedimento é falta de acesso ao sistema.
- Diferenciado número do pedido de verificação de identidade.
- Esclarecida a contagem de linhas e a proibição de inventar contatos, links ou telas.

Limite da verificação: as simulações demonstram o comportamento proposto; não garantem desempenho em todos os casos. Uma implantação deverá testar também sistemas conectados, autenticação e transferência real.
