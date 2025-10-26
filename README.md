## 📊Analise de Camapanha de Marketing

Fui Solicitado para fazer uma análise de uma campanha de marketing, o gestor chegou com o seguinte questionamento:

"Por que o CPA aumentou de forma significativa no ultimo mês?".

- Nosso **Principal objetivo** é explorar relações entre métricas de performance e identificar fatores que influenciam o custo por aquisição(CPA)

---

## 📈Métricas Analisadas

- Impressions: Número de vezes que o anúncio foi exibido
- Reach: Número de pessoas únicas alcançadas
- Frequency: Frequência média de exposição por pessoa
- Clicks: Número total de cliques
- CTR (%): Taxa de cliques (Click-Through Rate)
- Conversions: Número de conversões
- Spend (R$): Investimento em mídia
- CPC (R$): Custo por clique
- CPA (R$): Custo por aquisição (variável target)
- ROAS: Retorno sobre investimento em anúncios

---

## 🔬Análises Realizadas

- Essa tabela traz a Distribuição das Métricas spend, conversions, cpa e roas ao longo dos meses
e podemos observar que teve um aumento relevante do CPA nu ultimo mês confirmando o questionamento feito pelo Gestor

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>month</th>
      <th>spend</th>
      <th>conversions</th>
      <th>cpa</th>
      <th>roas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2025-04</td>
      <td>24669.95</td>
      <td>803</td>
      <td>31.268333</td>
      <td>3.944667</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2025-05</td>
      <td>28729.69</td>
      <td>896</td>
      <td>32.616774</td>
      <td>3.795806</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2025-06</td>
      <td>29564.50</td>
      <td>852</td>
      <td>35.309333</td>
      <td>3.483667</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2025-07</td>
      <td>32024.88</td>
      <td>849</td>
      <td>38.222903</td>
      <td>3.302258</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2025-08</td>
      <td>35157.26</td>
      <td>786</td>
      <td>45.400645</td>
      <td>2.738710</td>
    </tr>
    <tr>
      <th>5</th>
      <td>2025-09</td>
      <td>42867.13</td>
      <td>397</td>
      <td>118.079000</td>
      <td>1.155333</td>
    </tr>
  </tbody>
</table>
</div>

## Gráficos

- Esses gráficos mostram de forma visual o comportamento das métricas CPA e ROAS durante os meses
- Podemos observar que existe um correlação inversa entre as duas métricas conforme o CPA aumenta o ROAS cai, isso significa que quanto mais a gente paga para fazer uma venda, menor é o nosso retorno, ou seja, a campanha não está trazendo um retorno esperado.

<Figure size 640x480 with 1 Axes><img width="574" height="491" alt="image" src="https://github.com/user-attachments/assets/a45f5e40-e2c6-4b1a-ab73-1766af15fc24" />

<Figure size 640x480 with 1 Axes><img width="570" height="491" alt="image" src="https://github.com/user-attachments/assets/364fbf79-fcb3-463b-ab48-4510fac6c9d6" />


