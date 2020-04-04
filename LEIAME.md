# Impacta
**Inovação aberta para solucionar desafios do setor público**

*For English, click [here](https://github.com/mp-rj/Impacta/blob/master/README.md).*

**Ninguém inova sozinho**. Há um enorme potencial para solucionar desafios complexos de governo quando se abre caminho para a inteligência coletiva. Essa é a promessa da inovação aberta, processo que subverte a lógica tradicional de muitas decisões e compras governamentais. Ao invés de especificar a solução desejada, o órgão público define o desafio e o resultado esperado, garantindo à sociedade - Academia, empresas, startups etc. - a oportunidade de cocriar soluções. Em se tratando de soluções digitais e com novas tecnologias, o potencial da inovação aberta é ainda maior.

O **Impacta** é um projeto experimental de inovação aberta do Laboratório de Inovação do Ministério Público do Estado do Rio de Janeiro (Inova_MPRJ). Seu objetivo é explorar e testar o que há de mais avançado em programas de inovação aberta para governos - no Brasil e no exterior. Com o aprendizado, o Inova_MPRJ espera sugerir novas práticas e políticas de compras, planejamento estratégico e parcerias - não só para o MPRJ, mas para todo e qualquer órgão de governo. Queremos produzir, inclusive, propostas de aperfeiçoamento do ambiente regulatório da inovação.

## O que eu encontro neste repositório?
A inovação do programa começa em seu passo inicial. Estamos construindo a primeira versão e conduziremos ciclo de inovação aberta inaugural do MPRJ de forma colaborativa e 100% transparente. Buscamos chegar ao nível máximo de conformidade com os padrões de dados de contratos abertos da **[Open Contracting Partnership (OCP)](https://www.open-contracting.org/)** - algo [até então inédito](https://web.archive.org/web/20200404154540/https://www.open-contracting.org/worldwide/) no Brasil.

Neste repositório, você vai encontrar todo o registro de contratações do programa, desde a contratação da aceleradora que irá gerenciar o programa. Todos os arquivos estão em formato JSON e são compatíveis com o [Open Contracting Data Standard (OCDS)](https://standard.open-contracting.org/latest/en/) versão 1.1. Na pasta [records](https://github.com/mp-rj/Impacta/blob/master/records) é possível encontrar o registro consolidado com as informações mais recentes das contratações, enquanto a pasta [release-packages](https://github.com/mp-rj/Impacta/blob/master/release-packages) contém todo o histórico de atualizações relativo a esses processos. Estão disponíveis nessas pastas informações relativas aos seguintes processos:
- **ocds-e5r943-2020000234749**: Processo de contratação de Aceleradora para gerenciar o programa de inovação aberta do MPRJ (Impacta).


## Como utilizar os dados
A Open Contracting Partnership mantém um [diretório de ferramentas](https://airtable.com/shrzycSNYRcmV0WSZ/tblhHNGcDXuievZ74?blocks=hide) reutilizáveis para consumir e visualizar dados compatíveis com os padrões OCDS. Também recomendamos visitar a [galeria de projetos](https://airtable.com/shrsJ2QRVrpUaUWLf/tblhHNGcDXuievZ74?blocks=hide), onde é possível se inspirar com as diferentes soluções que comunidades ao redor do mundo têm criado a partir dos dados de contratações abertas.


## Como contribuir
Se você se interessou pelo programa de inovação aberta do MPRJ e quer saber mais, visite o [site do Impacta](https://www.mprj.mp.br/inova/impacta). Lá você encontra as últimas informações sobre o projeto, bem como as formas de participar.

Se você também se interessa pelo tema das contratações abertas e tem uma sugestão para impulsionar essa agenda no estado do Rio de Janeiro e no Brasil, entre em contato conosco pelo nosso e-mail: [inova@mprj.mp.br](inova@mprj.mp.br). Estamos sempre buscando novas parcerias!

Se você tem alguma observação específica sobre os dados nesse repositório ou sobre a nossa implementação do OCDS, você também pode mandar um e-mail - ou então [abrir uma Issue](https://github.com/mp-rj/Impacta/issues) aqui no GitHub. Vamos tentar responder assim que possível.


## Política de publicação

### Quem é responsável pelos dados?
O Inova_MPRJ é responsável por atualizar as informações sobre o programa e as respectivas contratações. A maneira mais fácil de falar com a equipe do Laboratório é pelo e-mail: **[inova@mprj.mp.br](mailto:inova@mprj.mp.br)**. Se preferir, você também pode nos visitar na [Av. Mal. Câmara, 370 - 4º andar - Castelo, Rio de Janeiro, RJ](https://www.openstreetmap.org/node/7184338297).

### De onde vêm os dados que estão aqui? Com que frequência eles são alimentados?
Os dados no repositório devem refletir os principais aspectos das contratações existentes nos respectivos processos administrativos. Porém, atualmente, não há extração automatizada a partir dos sistemas de gestão de processos do MPRJ. Por hora, os lançamentos (*releases*) serão gerados manualmente pela equipe do Laboratório, sempre que possível com atualizações antes e depois das principais fases das contratações: minuta de plano de contratação, definição do termo de referência, publicação do edital, licitação, contratação e execução dos marcos-chave do contrato.

### Exceções à publicidade das informações
Não há sigilo previsto para as contratações do programa Impacta. A [Lei de Licitações e Contratos](https://www.lexml.gov.br/urn/urn:lex:br:federal:lei:1993-06-21;8666) impõe apenas o sigilo  quanto ao conteúdo das propostas, até a respectiva abertura. 

A publicidade dos processos de contratação **não se estende** ao conteúdo detalhado das soluções geradas no programa de inovação aberta. O processo de contratação definirá cláusulas específicas sobre propriedade intelectual das soluções, podendo inclusive prever hipóteses de sigilo industrial e/ou comercial. O mesmo vale para os dados cedidos pelo MPRJ aos participantes do programa, que podem estar sujeitas a políticas específicas de proteção de dados pessoais e/ou sigilosos.

### Adaptações às listas controladas e abordagem de internacionalização
A implementação do padrão OCDS para as contratações do Impacta deve ser considerada experimental. Estamos trabalhando com todas as ferramentas oferecidas pela OCP para garantir total interoperabilidade com as ferramentas que utilizam esse padrão. Ainda assim, é provável que algumas adaptações sejam necessárias para lidar com a realidade regulatória brasileira e com as especificidades do próprio programa.

Alguns pontos que o usuário deve levar em conta ao consumir os dados:
- Os arquivos gerados usam o padrão OCDS com as propriedades em inglês, uma vez que ainda não há tradução do padrão para português. A linguagem principal para os valores das propriedades, por outro lado, é o português brasileiro. Nomes, descrições e demais propriedades compostas por textos livres geralmente estão traduzidos para o inglês, e são indicadas com o sufixo "_en".
- Atualmente, o padrão OCDS recomenda utilizar os códigos da iniciativa [org-id](http://org-id.guide/) para identificar as partes da contratação. Porém, esse repositório não inclui os identificadores mais utilizados no Brasil, como CPF e CNPJ (embora haja [uma proposta sobre isso](https://github.com/org-id/register/issues/365)). Enquanto a organização responsável por manter o registro do org-id [não estiver aceitando novas listas](https://github.com/org-id/register/tree/ee6179b02071c60e516202635a94e0b6782cf6e9#current-status-as-of-18th-december-2019), utilizamos o prefixo OCDS para identificar as partes (preferencialmente), ou o código extra-oficial "BR-CNPJ" - ou "BR-CPF" -, que fazem referência aos [cadastros da Secretaria da Receita Federal do Brasil](http://receita.economia.gov.br/orientacao/tributaria/cadastros). 
- As listas de unidades recomendadas pelo OCDS para quantificar os itens nas contratações - o [UNCEFACT](http://www.unece.org/fileadmin/DAM/cefact/recommendations/rec20/Rec20rev14e-Annex_II-III_2020.xls) e o [QUDT](http://www.qudt.org/qudt/owl/1.0.0/unit/Instances.html) - são apropriadas principalmente para o comércio de mercadorias físicas. Essas listas têm poucas opções para quantificar serviços, que são a maioria das contratações no programa. Partindo da premissa de que é melhor [publicar logo e melhorar depois](https://standard.open-contracting.org/latest/en/#open-contracting-data-standard-documentation), lançamos as primeiras versões do documento ainda sem as quantidades definidas conforme o padrão. [Aceitamos sugestões](#como-contribuir) de como lidar com essa questão.

### Planos para melhorar a qualidade dos dados
Os próximos passos para melhorar a transparência do programa e a sua compatibilidade com os padrões e melhores práticas em dados abertos incluem:
- Resolver a questão da quantificação dos serviços contratados ([ver acima](#adaptações-às-listas-controladas-e-abordagem-de-internacionalização));
- Registrar de maneira estruturada os comentários recebidos durante o processo de consulta pública da [Minuta do Plano de Contratação](https://drive.google.com/file/d/1qQPijADRnhI37EY16_HM0QksOasKaMI2);
- Manter o repositório atualizado com as últimas novidades do processo de contratação da Aceleradora para o programa - em especial, com os dados definidos em um futuro Termo de Referência;
- Estimular o uso dos padrões da OCDS entre outros órgãos da Administração Pública, bem como o consumo dos dados publicados pela sociedade civil e pela iniciativa privada. 