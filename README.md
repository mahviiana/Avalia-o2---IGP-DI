📈 Análise da Série Histórica do IGP-DI (2015–2024)
Este projeto apresenta uma análise da evolução do Índice Geral de Preços – Disponibilidade Interna (IGP-DI) entre 2015 e 2024, com dados obtidos diretamente do Banco Central do Brasil (SGS/BCB).

📊 Objetivo
Analisar a variação acumulada anual do IGP-DI.

Representar visualmente a série com um gráfico animado, utilizando gganimate.

Mostrar a importância do IGP-DI na economia brasileira.

🧾 Sobre o IGP-DI
O IGP-DI é calculado pela FGV e reflete variações de preços no atacado, ao consumidor e na construção civil. É amplamente utilizado para reajustes contratuais, avaliação de inflação ampla e formulação de políticas econômicas.

🛠️ Tecnologias Utilizadas
R / Quarto (.qmd)

rbcb, ggplot2, gganimate, gifski, lubridate, dplyr

📁 Estrutura do Projeto
site-IGP-DI.qmd: Código completo com gráfico animado e análise.

igpdi_animado.gif: Saída visual da animação.

README.md: Este arquivo.

🚀 Execução
Para rodar o projeto, instale os pacotes R necessários e compile o arquivo .qmd. O gráfico animado será salvo como .gif e exibido no HTML gerado.

🔗 Fonte de Dados
Banco Central do Brasil (Código SGS: 27815)

📌 Observação
Trabalho desenvolvido como parte da Avaliação 2 da disciplina de Visualização de Dados Econômicos
