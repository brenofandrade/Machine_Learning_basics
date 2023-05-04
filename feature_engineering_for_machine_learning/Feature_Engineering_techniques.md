# Feature Engineering Techniques
(Técnicas de Engenharia de Atributos)


Referências:

[Soledad Galli](https://www.linkedin.com/in/soledad-galli/) from Train in Data

> https://towardsdatascience.com/practical-code-implementations-of-feature-engineering-for-machine-learning-with-python-f13b953d4bcd
> https://trainindata.medium.com/best-resources-to-learn-feature-engineering-for-machine-learning-6b4af690bae7
> https://www.blog.trainindata.com/feature-engineering-for-machine-learning/


Por quê é necessário fazer __Engenharia de Atributos__?

Antes de começar a descrever as diversas técnicas, vamos entender as motivações e quando se deve aplicar cada técnica.

A resposta mais curta para essa pergunta é que as funções dos pacotes de _Machine Learning_ tanto do R, quanto em Python, esperam receber os dados de um determinado jeito. Isso quer dizer que se não entregar os dados formatados e processados aos algoritmos ou receberá uma bela mensagem de erro ou pior, obterá um modelo que não captura a tendência dos dados e pode levar a um mal entendimento do seu negócio ou acabar com sua reputação como cientista de dados :worried:

Problemas com dados:

- Valor ausente (_Missing Values_)
- Valor discrepante (_Outliers_)
- Escalas diferentes
- Tipos de variáveis inadequadas
- Codificação de variáveis categóricas
- Gerar novos atributos a partir dos já existentes