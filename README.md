Primeira avaliação Lógica de programação - Bruno Azevedo
Este notebook contém as soluções para a primeira avaliação de Lógica de Programação. Ele aborda exercícios de manipulação de listas, estruturas condicionais e laços de repetição para resolver problemas práticos de classificação de dados, avaliação de alunos, monitoramento de consumo de energia e simulação de carrinho de compras.

Questão 1 — Classificação de Temperaturas
Descrição:
Este segmento do notebook classifica uma lista de temperaturas diárias em categorias de 'Frio', 'Agradável' ou 'Quente' com base em regras predefinidas e, em seguida, contabiliza o número de dias em cada categoria.

Tarefas:
Classificar cada temperatura na lista.
Contar a ocorrência de temperaturas em cada categoria.
Entrada:
temperaturas = [18, 22, 30, 35, 28, 15, 40]

Regras de Classificação:
Temperaturas < 20 são classificadas como "Frio".
Temperaturas 20 <= temp <= 30 são classificadas como "Agradável".
Temperaturas > 30 são classificadas como "Quente".
Saída Principal:
Classificações: ['Frio', 'Agradável', 'Agradável', 'Quente', 'Agradável', 'Frio', 'Quente']
Contagem por Categoria: Frio: 2 dias, Agradável: 3 dias, Quente: 2 dias
Questão 2 — Sistema de Avaliação de Alunos
Descrição:
Este segmento do notebook avalia uma lista de notas finais de alunos, classificando-os como 'Reprovado', 'Recuperação' ou 'Aprovado' com base em critérios definidos. Em seguida, calcula a quantidade de alunos aprovados e o percentual de reprovados.

Tarefas:
Gerar lista de classificações para as notas.
Calcular a quantidade de alunos aprovados.
Calcular o percentual de alunos reprovados.
Entrada:
notas = [4.5, 6.0, 7.8, 9.0, 5.5, 8.2]

Regras de Classificação:
Notas < 5 são classificadas como "Reprovado".
Notas 5 a 7 (inclusive) são classificadas como "Recuperação".
Notas > 7 são classificadas como "Aprovado".
Saída Principal:
Classificações das notas: ['Reprovado', 'Recuperação', 'Aprovado', 'Aprovado', 'Recuperação', 'Aprovado']
Quantidade de alunos aprovados: 3
Percentual de reprovados: 16.67%
Questão 3 — Monitoramento de Consumo de Energia
Descrição:
Este segmento do notebook monitora o consumo diário de energia, classificando cada dia em 'Baixo', 'Moderado' ou 'Alto' com base em regras definidas. Ele também calcula o consumo total e a média semanal, e verifica se é necessário emitir um alerta para consumo excessivo.

Tarefas:
Classificar cada consumo diário.
Filtrar dias com consumo alto.
Calcular o total de consumo da semana.
Calcular a média semanal de consumo.
Exibir alerta se houver mais de 2 dias com consumo alto.
Entrada:
consumo = [120, 95, 200, 180, 75, 220, 160]

Regras de Classificação:
Consumo < 100 é classificado como "Baixo".
Consumo 100–180 (inclusive) é classificado como "Moderado".
Consumo > 180 é classificado como "Alto".
Saída Principal:
Classificações de consumo: ['Moderado', 'Baixo', 'Alto', 'Moderado', 'Baixo', 'Alto', 'Moderado']
Total de consumo da semana: 1050 kWh
Média semanal de consumo: 150.00 kWh
Questão 4 — Simulação de Carrinho de Compras
Descrição:
Este segmento do notebook simula um carrinho de compras, aplicando regras de desconto específicas a uma lista de preços de itens. Ele calcula os preços finais após os descontos, o valor total da compra e a economia total obtida.

Tarefas:
Criar uma lista com os preços finais dos itens após aplicar os descontos.
Calcular o total da compra com os descontos aplicados.
Calcular a economia total obtida na compra.
Entrada:
precos = [50, 120, 30, 200, 80, 15]

Regras de Desconto:
Itens com preço < 50 recebem 5% de desconto.
Itens com preço 50–150 (inclusive) recebem 10% de desconto.
Itens com preço > 150 recebem 15% de desconto.
Saída Principal:
Preços finais com desconto: ['45.00', '108.00', '28.50', '170.00', '72.00', '14.25']
Total da compra com desconto: 437.75
Economia total obtida: 57.25
Instruções de Uso
Para utilizar este notebook:

Abra o Notebook: Faça o download ou abra o arquivo .ipynb em um ambiente Jupyter (como Jupyter Notebook, JupyterLab ou Google Colab).
Execute as Células: Execute as células de código sequencialmente. Cada célula contém um problema e sua respectiva solução em Python.
Analise os Resultados: Observe as saídas impressas para entender as classificações, cálculos e alertas gerados por cada questão.
Explore o Código: Sinta-se à vontade para modificar as listas de entrada (temperaturas, notas, consumo, precos) e experimentar com diferentes valores para ver como o comportamento do código se altera.
