# Projeto-4-Analise-Bancaria
 O objetivo desta análise é tentar descobrir as principais causas que levaram um número expressivo de clientes à cancelarem seus cartões de crédito.
#
 Dados retirados do site : https://www.kaggle.com/sakshigoyal7/credit-card-customers
 #
Descrição do código:

- Primeiro passo desse processo foi entender como estava disposto os dados e se havia informações irrelevantes para a análise.
- Em seguida, após a análise preliminar, retirei a única coluna que não teria utilidade para a análise.
- Após isso foi preciso verificar mais afundo as informações contidas nos dados, afim de identificar se havia dados faltates na tabela e tratá-los.
- Após o tratamento, foi feito uma análise preliminar dos dados verificando: média, valores mínimos e máximos, desvio padrão e os quartis.
- Para direcionar melhor a análise, trabalhei com uma coluna que serviu de base para as demais análises. Essa coluna foi a de "Categoria", onde procurei identificar os clientes que ainda eram usuários ativos e os que já haviam cancelado os serviços.
- Verifique a quantidade dessas duas categorias em valores absolutos e depois em porcentagem.
- Finalizando o processo, criei um loop para analisar cada coluna comparando nelas o perfil dos clientes com base na "Categoria", ou seja, em cada coluna foi comparado o dado que a coluna armazenava corelacionando entre ativos/inativos.
- O grafico que melhor se encaixou para esse processo foi o de histograma. (Poderia ser também o de colunas empilhadas)

#

Conclusão da análise a partir da plotagem dos gráficos:

- A maioria dos cancelamentos estão situados na categoria de cartão "Blue".
- Clientes com limite baixo tendem a cancelar o cartão.
- Clientes que possuem transações baixas tem uma alta taxa de cancelamento do cartão.
- Clientes que não utilizavam o cartão tenderam ao seu cancelamento.
- Clientes que entraram em contato com o SAC mais de 3 vezes tenderam a cancelar o cartão (o que mostra a insatisfação com o serviço)
