test001: Validação de entrada de números.
entrada: -1.
retorno_esperado: Exibição de mensagem de erro sem travar o sistema.
resultado: O código não apresentou nenhuma mensagem de erro. Prosseguiu mesmo o número sendo negativo.

test002: Validação de entrada de números.
entrada: 10.
retorno_esperado: Exibição do valor final.
resultado: O código apresentou o valor final, sem aplicação de desconto.

test003: Testando entrada de valor com letras.
entrada: b.
retorno-esperado: Exibição de mensagem de erro sem travar o sistema.
resultado: De acordo com o resultado esperado.

test004: Testando entrada de valor com letras na parte de desconto.
entrada: 10, a.
retorno_esperado: Exibição de mensagem de erro sem travar o sistema.
resultado: De acordo com o resultado esperado.

test005: Testando entrada de número na parte de desconto.
entrada: 10, 50.
retorno_esperado: Exibição do valor final com desconto aplicado.
resultado: Exibição do valor final sem desconto aplicado.
