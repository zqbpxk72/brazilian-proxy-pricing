# comprar proxies brasileiros: o que checar antes de pagar por GB e como testar IPs do Brasil sem assinatura mensal

Quem pesquisa "comprar proxies brasileiros" raramente quer uma aula sobre o que é um proxy. A pergunta prática é outra: como conseguir IPs que o Mercado Livre, a Amazon BR, o Magalu, o iFood e o Google.com.br tratem como um usuário comum de São Paulo, sem assinar um plano mensal que vai vencer com metade do tráfego sobrando.

É aí que quase todo mundo trava. Os provedores maiores cobram de US$ 4 a US$ 8 por GB e vendem por assinatura. Os mais baratos anunciam centavos por GB, mas nem sempre entregam IPs brasileiros limpos. E existe uma terceira faixa, que a DataImpulse ocupa: pagamento por uso, US$ 1/GB no residencial, tráfego que não expira e sem mensalidade. Os detalhes dessa faixa — o que ela resolve, onde ela cobra mais e quando ela não serve — são o assunto deste texto.

## O que você está comprando quando o proxy precisa ser brasileiro

Existem quatro tipos de IP no mercado, e a diferença entre eles muda o preço e o resultado:

- **Residencial**: IP distribuído por provedores como Vivo, Claro e TIM para casas de verdade. Sites tratam como tráfego legítimo. É o tipo que funciona para raspagem de e-commerce, acompanhamento de preços e monitoramento de SERP.
- **Móvel (3G/4G/5G)**: IP de operadora celular. Mais difícil de bloquear, mais caro, usado em automação de redes sociais e teste de apps.
- **Datacenter**: IP de servidor. Rápido e barato, mas fácil de identificar. Serve para alvos que não exigem cara de usuário real.
- **ISP / residencial estático**: IP fixo com aparência residencial, muito usado em multicontas. Nem todo provedor oferece.

O ponto que costuma passar batido: um IP residencial dos Estados Unidos fingindo ser brasileiro não engana os sistemas locais por muito tempo. Preço em real, frete calculado por CEP, conteúdo liberado só para quem está no país — tudo isso é decidido pelo IP de saída. Sem IP nacional, a coleta sai errada.

## Quanto custa comprar proxy brasileiro: a faixa real de preço

Preços de tabela anunciados pelos próprios provedores, para proxies residenciais, modelo de pagamento por uso:

| Provedor | Preço inicial por GB | Preço por GB em 1 TB |
| --- | --- | --- |
| Geonode | a partir de US$ 0,27 | por volume, sob consulta |
| DataImpulse | US$ 1,00 | US$ 0,80 |
| Decodo | ~US$ 4,00 | US$ 2,00 (assinatura mensal) |
| IPRoyal | US$ 7,35 | US$ 3,31 |
| Oxylabs | ~US$ 8,00 | US$ 4,00 |
| Bright Data | ~US$ 8,00 (padrão) | ~US$ 4,00 (promocional) |

Duas leituras rápidas dessa tabela. A primeira: existe um degrau enorme entre "provedor de entrada" e "provedor corporativo", e a diferença nem sempre está no IP em si, mas em camadas que a maioria dos projetos de scraping nunca usa — painel de compliance, gerente de conta, API gerenciada. A segunda: o preço por GB não é a única variável. Cobrança por assinatura significa que GB não usado vira prejuízo todo mês.

Vale conferir os valores atualizados direto na fonte antes de fechar orçamento, porque essas faixas se mexem com frequência: 👉 [ver os preços atuais por GB e os pacotes disponíveis](https://dataimpulse.com/residential-proxies/?aff=86938).

## Por que o modelo de cobrança pesa mais que o preço

Um projeto típico de coleta no Brasil não consome tráfego de forma constante. Tem semana de pico, tem mês parado esperando aprovação de cliente. Se o modelo é assinatura mensal, os GB não usados evaporam no fim do ciclo e você paga de novo.

O modelo de pagamento por uso resolve isso de forma simples: você compra um volume, ele fica no saldo, e a fatura acompanha o consumo. É o argumento central da DataImpulse — o tráfego comprado não expira, não existe assinatura obrigatória e a segmentação por país já está incluída no preço base. Se você compra 50 GB hoje e usa 10 GB nesta semana e 40 GB nas próximas seis, ninguém confisca nada.

Duas observações que as páginas de vendas não destacam tanto. A primeira compra mínima é de US$ 5. A partir da segunda compra, o mínimo sobe para US$ 50 — o que, no residencial, equivale a 50 GB, no móvel a 25 GB e no datacenter a 100 GB. Como o tráfego não expira, isso é mais uma questão de caixa do que de prazo apertado, mas quem faz trabalhos pequenos precisa saber que a recarga seguinte não pode ser de US$ 10.

## Todos os planos publicados pela DataImpulse hoje

A DataImpulse não vende "planos bronze, prata e ouro". Ela vende tráfego, separado por tipo de proxy. A grade completa, com preço e ciclo de cobrança, fica assim:

| Plano / pacote | Tipo | Preço | Ciclo | Comprar |
| --- | --- | --- | --- | --- |
| Intro — 5 GB | Residencial | US$ 5 (US$ 1/GB) | pagamento único, sem assinatura | [abrir o pacote de teste](https://dataimpulse.com/residential-proxies/?aff=86938) |
| Padrão por GB | Residencial | US$ 1,00/GB | conforme o uso | [ver o residencial por GB](https://dataimpulse.com/residential-proxies/?aff=86938) |
| Volume — 1 TB | Residencial | US$ 800 (US$ 0,80/GB) | pagamento único | [ver o plano de 1 TB](https://dataimpulse.com/residential-proxies/?aff=86938) |
| Volume — 5 TB | Residencial | US$ 0,70/GB | pagamento único | [consultar volume maior](https://dataimpulse.com/residential-proxies/?aff=86938) |
| Intro — 1 GB | Residencial Premium | US$ 5 (US$ 5/GB) | pagamento único | [testar o premium](https://dataimpulse.com/premium-residential-proxies/?aff=86938) |
| Basic — 10 GB | Residencial Premium | US$ 50 (US$ 5/GB) | sem mensalidade | [ver o premium Basic](https://dataimpulse.com/premium-residential-proxies/?aff=86938) |
| Custom — 1.000 GB | Residencial Premium | US$ 4.000 (~US$ 4/GB) | sem mensalidade | [ver o premium para volume](https://dataimpulse.com/premium-residential-proxies/?aff=86938) |
| Custom — 5 TB+ | Residencial Premium | preço negociado | sob consulta | [falar sobre o premium custom](https://dataimpulse.com/premium-residential-proxies/?aff=86938) |
| Basic | Datacenter | US$ 0,50/GB | conforme o uso | [ver o datacenter a partir de US$ 0,50/GB](https://dataimpulse.com/datacenter-proxies/?aff=86938) |
| 100 GB | Datacenter | US$ 50 | pagamento único | [abrir o pacote de 100 GB](https://dataimpulse.com/datacenter-proxies/?aff=86938) |
| 1 TB | Datacenter | US$ 450 (US$ 0,45/GB) | pagamento único | [ver o datacenter de 1 TB](https://dataimpulse.com/datacenter-proxies/?aff=86938) |
| 5 TB+ | Datacenter | a partir de US$ 2.250 | sob consulta | [consultar volume de datacenter](https://dataimpulse.com/datacenter-proxies/?aff=86938) |
| Standard | Móvel | US$ 2,00/GB | conforme o uso | [ver os proxies móveis](https://dataimpulse.com/mobile-proxies/?aff=86938) |
| 2,5 GB | Móvel | US$ 5 | pagamento único | [testar o móvel por US$ 5](https://dataimpulse.com/mobile-proxies/?aff=86938) |
| 25 GB | Móvel | US$ 50 | pagamento único | [abrir o pacote de 25 GB](https://dataimpulse.com/mobile-proxies/?aff=86938) |
| 1 TB | Móvel | US$ 1.600 (US$ 1,60/GB) | pagamento único | [ver o móvel de 1 TB](https://dataimpulse.com/mobile-proxies/?aff=86938) |
| 5 TB+ | Móvel | a partir de US$ 8.000 | sob consulta | [consultar volume móvel](https://dataimpulse.com/mobile-proxies/?aff=86938) |

Alguns padrões que aparecem na tabela e valem comentário. A grade de residencial é quase plana: de 5 GB até cerca de 800 GB, a taxa segue em US$ 1/GB, e o único degrau de desconto real chega na casa dos mil GB. Ou seja, comprar 200 GB em vez de 50 GB não rende nenhum bônus intermediário — só muda o total da fatura. No móvel acontece o mesmo, num patamar mais alto: US$ 2/GB até cerca de 800 GB, US$ 1,60/GB a partir de 1 TB. O datacenter é o único com preço baixo desde a primeira compra: US$ 0,50/GB em toda a faixa.

## Os IPs brasileiros dentro da rede: o que os números oficiais mostram

Esse é o dado que separa "tem cobertura no Brasil" de "tem IP suficiente para o Brasil". Nas páginas de localidade da própria empresa, para o Brasil:

- **Residencial Premium**: cerca de 43 mil IPs ativos em tempo real, 584,8 mil IPs únicos nos últimos 30 dias e 87,9 mil IPs únicos nas últimas 24 horas.
- **Datacenter**: cerca de 2,9 mil IPs ativos, 18,6 mil IPs únicos em 30 dias.

A leitura prática: para o residencial premium, há rotação suficiente para tarefas contínuas de coleta sem repetir o mesmo IP a cada poucos minutos. O datacenter brasileiro é bem menor e mais previsível — serve para alvos fáceis, não para plataformas com defesa agressiva. A rede inteira é anunciada com mais de 90 milhões de IPs residenciais em 195 países, contando com cerca de 1 milhão de IPs ativos em tempo real a qualquer momento.

Quem quer ver a distribuição por país antes de pagar pode consultar a lista de localidades: 👉 [ver a cobertura por país e checar o pool do Brasil](https://dataimpulse.com/proxies-by-location/?aff=86938).

## Como apontar o tráfego para o Brasil (e não para "algum lugar da América Latina")

A configuração é feita no próprio nome de usuário do proxy, o que evita criar credenciais diferentes para cada país. O padrão documentado:

1. **País**: adicione `__cr.br` ao login. México seria `__cr.mx`, Argentina `__cr.ar`, e assim por diante.
2. **Cidade**: acrescente `;city.saopaulo` para mirar São Paulo especificamente.
3. **Sessão fixa**: use `;sessid.xxxx` quando precisar manter o mesmo IP durante um fluxo com login.
4. **Portas**: 823 para HTTP rotativo, 824 para SOCKS5 rotativo. Sessões sticky ficam na faixa 10000–20000.

Sobre duração de sessão, há uma divergência que vale registrar: a empresa divulga sessões sticky de até 30 minutos, enquanto a documentação técnica fala em intervalos de 1 a 120 minutos, com 30 minutos como padrão quando nada é especificado. Para coleta com login, teste o comportamento no seu alvo antes de assumir que a sessão vai durar duas horas.

Os protocolos suportados são HTTP(S) e SOCKS5, e a segmentação por país está incluída no preço base. Segmentações mais finas — estado, cidade, CEP e ASN — são cobradas à parte no residencial.

## Onde o preço baixo cobra a conta

Vale ser direto sobre as limitações, porque elas aparecem depois da compra, não antes:

**Segmentação avançada custa o dobro no residencial.** Estado, cidade, CEP e ASN são cobrados a 2× a taxa padrão por GB nos planos residenciais. Se o seu projeto precisa mirar CEP específico, esse US$ 1/GB vira US$ 2/GB efetivo. Existe uma inconsistência aqui: a página de produto do datacenter lista cidade/CEP/ASN como recursos incluídos, então o tratamento pode variar por tipo de proxy — confirme com o suporte antes de montar o orçamento.

**Não existem proxies ISP estáticos.** Se o seu caso é multicontas com identidade fixa, essa não é a ferramenta certa. A própria comparação publicada pela empresa diz que proxies ISP costumam ser mais adequados para essa finalidade. Não há como contornar isso com residencial rotativo.

**Não há API de scraping pronta nem endpoints gerenciados.** A DataImpulse entrega IP, credenciais e painel. A lógica de coleta é problema seu.

**Bancos e sites governamentais estão bloqueados por padrão.** A lista de bloqueio inclui domínios de instituições financeiras, .gov e algumas dezenas de outros sites. Desbloqueio exige verificação de identidade (KYC) e passa por níveis: .gov individuais após verificação, todos os .gov com verificação mais US$ 100 gastos, e sites bancários a partir de US$ 1.000 gastos, apenas para uso corporativo. Portas de e-mail como SMTP e IMAP também estão restritas.

**O mínimo da segunda compra é US$ 50.** Já mencionado, mas é o tipo de detalhe que estraga o planejamento de quem imagina recarregar de US$ 10 em US$ 10.

Nada disso é defeito escondido — está tudo na documentação pública. O problema é que quase ninguém lê a documentação antes de escolher o preço mais chamativo.

## Testar antes de escalar: o caminho de US$ 5

A sequência que evita compra errada:

1. Crie a conta e pegue as credenciais de residencial. O pacote de entrada é de 5 GB por US$ 5, e esse saldo não expira — se você usar 1 GB no primeiro teste, os outros 4 GB ficam esperando.
2. Configure o alvo em um único tipo de proxy por vez. Rodar residencial e datacenter em paralelo no mesmo teste só embaralha a comparação.
3. Meça taxa de sucesso nas URLs exatas que você precisa raspar, não em um site genérico de demonstração. Uma taxa de 99% em `httpbin` não diz nada sobre o Mercado Livre.
4. Só depois de validar, suba o volume. O degrau de desconto só existe a partir de 1 TB, então para a maioria dos projetos o escalonamento é linear mesmo.

Listagens de terceiros mencionam garantia de reembolso de 7 dias na primeira compra. Como isso não aparece de forma destacada na página de vendas, é uma daquelas coisas para confirmar no chat de suporte antes de pagar — o atendimento humano funciona 24/7, com tempo médio de resposta na casa de poucos minutos.

Para começar pelo teste de 5 GB: 👉 [criar conta e testar os proxies brasileiros por US$ 5](https://bit.ly/dataimPulse).

## Como isso se compara ao resto do mercado

Reputação de terceiros: a DataImpulse aparece com nota 4,8/5 no G2 com mais de 500 mil clientes declarados, e listagens de 2024 registravam 4,6/5 no Trustpilot. Ganhou um prêmio de "Greatest Progress" da Proxyway. Não é um fornecedor sem histórico, o que importa quando o preço é muito abaixo da média.

Resumo honesto:

**A favor** — US$ 1/GB é o menor preço entre provedores legítimos de residencial; tráfego que não expira elimina desperdício de assinatura; pool de primeira parte (menos histórico de abuso compartilhado); segmentação por país incluída; suporte humano 24/7; cobertura brasileira residencial decente para coleta contínua.

**Contra** — sessões sticky curtas comparadas a concorrentes que oferecem 24 horas; sem proxies ISP; sem API de scraping; segmentação fina a 2× no residencial; mínimo de US$ 50 na segunda compra; móvel e premium só ganham desconto de volume a partir de 1 TB.

Onde ele ganha na prática: projetos de scraping e monitoramento de preços no Brasil com volume imprevisível. Onde ele perde: operações de multicontas que precisam de IP fixo de aparência residencial, e times que já dependem de API de scraping gerenciada.

## Perguntas que aparecem antes de clicar em comprar

**Preciso de assinatura mensal?** Não. O modelo é pagamento por uso, por GB, sem plano recorrente obrigatório.

**O tráfego que eu comprar expira?** Não. O saldo fica na conta até ser consumido, sem reset mensal. Isso significa que comprar volume maior para travar o preço atual faz sentido financeiro, mas só se o consumo realmente existir.

**Qual tipo serve para Mercado Livre, Amazon BR, Magalu e iFood?** Residencial para a maior parte das tarefas de coleta e acompanhamento de preços. Móvel quando a plataforma tem defesa agressiva ou quando o alvo é um fluxo de app.

**Consigo mirar cidade específica no Brasil?** Sim, com `;city.saopaulo` ou equivalente, mas no residencial isso entra na faixa de segmentação avançada, cobrada a 2× o preço por GB.

**Tem proxy ISP estático?** Não. Esse é o limite mais relevante para quem trabalha com multicontas.

**Quanto é o mínimo para começar?** US$ 5 no primeiro pacote. A partir da segunda compra, US$ 50.

**Serve para raspagem de dados de bancos?** Não. Domínios bancários e governamentais estão bloqueados, com desbloqueio condicionado a verificação de identidade e níveis de gasto.

## Resumindo

Comprar proxies brasileiros é uma decisão de três variáveis: tipo de IP, preço por GB e o que acontece com o tráfego que você não usa. A DataImpulse acerta nas três com US$ 1/GB no residencial, IPs brasileiros suficientes para rodar coleta contínua e um modelo de pagamento que não pune mês fraco. Ela não serve se o seu caso exige IP fixo residencial, sessões longas de várias horas ou API de scraping pronta.

Para quem faz scraping, monitoramento de preço ou verificação de anúncios no mercado brasileiro e quer medir o custo real por requisição bem-sucedida antes de escalar: 👉 [ver todos os planos e comprar proxies brasileiros a partir de US$ 1/GB](https://bit.ly/dataimPulse).
