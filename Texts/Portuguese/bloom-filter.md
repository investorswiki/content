---
keywords: Crypto
title: Filtro Bloom
description: Filtro Bloom. Uma estrutura de dados que pode ser usada para informar ao usuário se um determinado item faz parte de um conjunto de itens
---

# Filtro Bloom
Um filtro Bloom é uma estrutura de dados que pode ser usada para informar ao usuário se um determinado item faz parte de um conjunto. Embora não possa dizer com certeza se um elemento está no conjunto, pode dizer com certeza se o elemento não está.

Criados por Burton Howard Bloom em 1970, os filtros Bloom são uma oferta atraente para uma variedade de aplicações devido à sua eficiência no uso do espaço. Em algumas criptomoedas (mais notavelmente Bitcoin), elas desempenham um papel integral na Verificação de Pagamento Simplificada, ou SPV.

Ao usar um cliente SPV, os usuários podem interagir com a rede Bitcoin sem executar um nó completo. Os nós completos vêm com certos requisitos computacionais e de armazenamento que os tornam difíceis de serem executados em dispositivos de baixa potência, como smartphones. Os clientes SPV, por outro lado, simplesmente consultam nós completos para obter informações relevantes para a(s) carteira(s) do usuário.

A solução mais direta para retransmitir esses dados para o usuário seria tornar os nós completos cientes das chaves do cliente, de modo que apenas as transações pertinentes sejam enviadas a eles. Evidentemente, esta é uma solução abaixo da média, pois a privacidade do cliente seria sacrificada. Por outro lado, baixar todas as transações apenas para descartar a maioria delas seria um desperdício de largura de banda. Insira os filtros Bloom.

Vamos ilustrar. Suponha que um cliente, Alice, tenha uma transação de alto valor que ela não quer que Bob, que executa um nó completo, esteja ciente. Ela constrói um filtro Bloom, que ilustraremos como uma grade 10x1:

Ela passa os dados da transação em que está interessada por meio de duas funções hash diferentes, que geram dois números entre 0 e 9. Vamos chamá-los de 4 e 7. Ela envia o filtro para Bob.

Olhando para esta grade, você não tem ideia de quais dados Alice passou para o filtro. Se você tivesse um conjunto no qual os dados estivessem contidos, você poderia fazer um hash e compará-lo com o filtro – se houver uma correspondência, existe a possibilidade de que seja a informação que Alice solicitou.

Ao mesmo tempo, é provável que haja muitas entradas mapeadas para 4 e 7, de modo que Bob não pode determinar em qual parte dos dados Alice está interessada. Ele simplesmente retorna todas as correspondências e Alice as filtra do lado dela.

Isso é, obviamente, uma simplificação grosseira, mas demonstra o conceito: os filtros Bloom ofuscam os verdadeiros interesses do cliente. Não é um método perfeito (ainda há preocupações com sua privacidade), mas é uma melhoria em relação a uma solicitação não blindada a um nó.

