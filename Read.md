*Sistema de Gestão de IPTU da Prefeitura de SimCity
**Este sistema foi desenvolvido para automatizar os processos de cobrança de IPTU da Prefeitura de SimCity através de um cadastro digitalizado de imóveis.

**Características do Imóvel
Cada imóvel possui as seguintes características:

*Matrícula: Identificação única do imóvel.
*Lista de proprietários: Nomes dos proprietários do imóvel.
*Tipo de Imóvel: Pode ser casa, apartamento ou terreno.
*Valor venal: Valor de mercado do imóvel.
*Área em metros quadrados: Tamanho do imóvel em metros quadrados.
*Funcionalidades do Sistema
*O sistema deve permitir a gestão dos imóveis através das seguintes funcionalidades:

*Cadastro: Permite a inclusão de novos imóveis no sistema.
*Listagem: Exibe todos os imóveis cadastrados.
*Consulta por matrícula: Permite buscar informações de um imóvel específico usando a matrícula.
*Remoção por código de matrícula: Permite excluir um imóvel do sistema usando a matrícula.
*Cálculo do valor do IPTU: Calcula o valor do IPTU com base nas seguintes condições:
*Cálculo do IPTU
Casa:
Até 200m²: metragem * 5 + 200 + 5% do valor venal
Acima de 200m²: metragem * 6 + 350 + 8% do valor venal
Terreno:
Até 400m²: metragem * 3 + 500
Acima de 400m²: metragem * 10 + 500
Apartamento:
Até 150m²: metragem * 2 + 200 + 3% do valor venal
Acima de 150m²: metragem * 4 + 350 + 10% do valor venal
Listagem do Valor Total dos Imóveis
Valor venal total por tipo de imóvel: Lista o valor total dos imóveis agrupados por tipo (casa, apartamento, terreno).
Cálculo do Imposto
O sistema deve calcular o imposto do ano corrente e dos próximos 5 anos, com um acréscimo de 7% a cada ano.

Padrão de Desenvolvimento
O sistema utiliza o padrão MVC (Model-View-Controller) para separar as responsabilidades em diferentes camadas:

Model: Lida com a lógica de negócios e a interação com os dados.
View: Responsável pela apresentação dos dados.
Controller: Interpreta as entradas do usuário e chama a lógica de negócios apropriada no Model.