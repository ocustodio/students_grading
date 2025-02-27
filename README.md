# Analisando o Desempenho de Estudantes - Projeto de Aprendizado
## O objetivo deste projeto é analisar a performance dos alunos de uma escola fictícia, e poder fazer recomendações para a melhora do desempenho acadêmico dos alunos.

Esse dataset é **totalmente fictício**, tirado do site [kaggle](https://www.kaggle.com/). Os dados foram gerados de forma aleatória, tornando a análise e a geração de insights menos consistente, também possuindo alguns outliers e dados faltosos, onde foram devidamente tratados. O intuito deste projeto é **somente para aprendizado**, e nenhum insight, e recomendação deve ser levado a sério.

## Estrutura do Dataset
Esse dataset consiste somente de uma tabela com as informações dos alunos, como nome, idade, notas, nível de estresse e horas dormidas.

<img width="210" alt="image" src="https://github.com/user-attachments/assets/de8db9dd-7685-4093-b455-aa6a9d84f706">

## Insights
#### Para avaliar o desempenho dos alunos, nós focamos nas seguintes métricas:
- **Performance Acadêmica**:  avalia o desempenho dos alunos em várias dimensões, incluindo notas totais, participação, e a qualidade das entregas.
- **Fatores Demográficos**: avalia o desempenho dos alunos levando em consideração variáveis como sexo, idade e nível educacional dos pais.
- **Comportamento de Estudo e Bem-Estar**: avalia a relação entre os hábitos de estudo, qualidade do sono, níveis de estresse e desempenho acadêmico dos alunos.

#### Performance Acadêmica
- Entre todos os departamentos, o curso de matemática possui as maiores médias em 3 categorias (Total, Assignments e Participation) mas também possui as menores em outras 3 categorias (Final, Projects e Quizzes).
- A distribuição dos aluno, que possuem uma quantidade de horas de estudo por semana, com relação à média da nota total, em sua grande parte, está bem equilibrada, com outliers em ambos os eixos. Mas é possível ver uma pequena tendência de queda das médias conforme o número de horas estudadas aumenta.
- Apesar de a diferença na média da nota total ser muito pequena, alunos que normalmente não participam de atividades extracurriculares, possuem uma nota total maior.
  
#### Fatores Demográficos
- Alunos do sexo feminino, em sua grande parte, possuem uma média da nota total, maior que os alunos do sexo masculino.
- Alunos onde o nível de educação dos pais é de "ensino médio", possuem uma média da nota total maior, que o restante. Seguido por pais que possuem "PhD" e logo após, pais que não possuem nenhum nível educação.
- Os alunos mais velhos (24 anos) possuem as maiores médias da nota total, já os alunos mais novos (18 anos) possuem as menores médias da nota total.

#### Comportamento de Estudo e Bem-Estar
- Apesar de haver outliers nas duas extremidades dos dados, as menores médias da nota total, está concentrada na faixa de 4 a 7 horas dormidas por noite.
- Ambas as extremidades do nível de estresse possuem outliers, mas é possível analisar que alunos com um nível de estresse até o nível 5, possuem as maiores médias da nota total, comparado com os outros alunos.
- É possível analisar que os alunos que dormem somente de 5 a 6 horas por noite possuem um nível de estresse maior que o restante. Também com o aumento de horas dormidas, é possível visualizar que, o nível de estresse apresenta uma diminuição.

## Recomendações
- **Revisar Avaliações Finais e Projetos**: o departamento de matemática por exemplo apresenta as três melhores medias e as três piores, pode haver uma desconexão no modo de avaliação entre os departamentos. Uma análise do formato e conteúdo dessas avaliações pode ser útil para identificar se há dificuldades específicas ou falta de preparo para avaliações de maior peso.
- **Otimização do Tempo de Estudo**: alunos que estudam mais horas não estão se saindo tão bem, isso pode indicar que eles estão estudando de forma ineficiente. Pode ser útil oferecer treinamentos sobre estratégias de estudo mais eficazes, como técnicas de estudo ativo, gestão do tempo, ou revisão de tópicos mais importantes.
- **Suporte a Alunos Mais Jovens**: alunos mais jovens podem estar enfrentando dificuldades de adaptação ao ambiente universitário, tanto em termos de habilidades de estudo quanto de gestão do tempo. Implementar programas de integração, como workshops sobre estudo, estratégias de gerenciamento do tempo, e apoio psicológico, pode ajudar a melhorar a performance desses alunos.
- **Promover Educação sobre Gestão do Tempo**: muitos alunos podem não estar conseguindo equilibrar estudos e descanso adequadamente. Oferecer workshops ou recursos sobre gestão do tempo, que ajudem os alunos a planejarem seu tempo de estudo sem sacrificar o sono.
- **Intervenções para Estresse Alto**: para alunos com estresse elevado, fornecer apoio psicológico, aconselhamento e recursos para reduzir a ansiedade pode ser uma boa estratégia para evitar que o estresse excessivo prejudique o desempenho.

## Dashboard
O dashboard pode ser achado no Power BI Web neste [link](https://app.powerbi.com/view?r=eyJrIjoiNTAzOGUzMTQtZGE0ZS00NTc0LTgxNzgtNTA4OTdmMmFmNzU1IiwidCI6ImQwYzY5OGQ0LWU0ZWEtNGVlOS1hNzlkLWYyZDdhNzgzOTljOCJ9). O dashboard permite usuários de filtrar, analisar tendencias, valores e métricas nos dados apresentados.

<img width="850" alt="image" src="https://github.com/user-attachments/assets/c7d7a593-7470-4603-97cd-80f265978bcf">


