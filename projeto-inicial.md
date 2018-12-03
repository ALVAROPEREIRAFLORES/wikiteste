<!-- TITLE: Release Notes -->
# Versão atual
## Versão `1.3.1`

- Data da liberação: **`14/11/2018 14:53`**
- OS’s atendidas:

## Novas funcionalidades

- N/A

## Melhorias

- Correção na barra do brasil ao adicionar o protocolo https.


## Correção de defeitos

- N/A

## Lista de Script SQL para serem executados

- N/A

## Objetos de implantação

```
Código Fonte:   (x) Sim ( ) Não
Banco de Dados: ( ) Sim (x) Não
```

---

# CHANGELOG

### 1.3.0 _(07/11/2018 17:33)_

- Compartilhamento de token em ambiente clusterizado
- Link para o sistema antigo

## 1.2.0 _(09/07/2018)_
- No Painel de Controle alteração do label valor disponível para Valor Priorizado.
- Na consulta da emenda listar apenas os tipos de modalidade que tem disponível na emenda.
- No cabeçalho do beneficiário remoção o termo RCL.
- No grid de beneficiários indicados alinhamento do campo Beneficiário à direita.
- No detalhar beneficiário subir a esfera e tipo para a linha do CNPJ.
- No cabeçalho de proposta retirada do termo RCL.
- No extrato da propostas alinhamento dos valores unitário e total à direita.
- No relatório consolidado remoção do termo "RCL" e o termo "do beneficiário".
- No campo montar relatório substituição do termo Disponível por priorizado.
- Ajuste no espaçamento do relatório padrão.
- Correção ao exibir a situação da proposta.
- Correção do valor empenhado no final do relatório padrão.

## 1.1.3 _(28/06/2018)_
- Correção ao buscar os senadores por email.

## 1.1.2 _(25/06/2018)_
- No relatório padrão o sistema está gerando data na língua inglesa e os valores em configuração distinta da moeda nacional;
- Os campos valor Empenhado e valor pago no relatório padrão não estão buscando dados atualizados.
- Correções e melhorias reportadas pelos gestores.
- Carga de foto dos parlamentares.

## 1.1.0 _(22/01/2018)_
- Inserção do número da nota de empenho no relatório padrão e personalizado
- Alterado nomenclatura do termo liberado para priorizado;
- Inserção do localizador da emenda no relatório padrão;
- Inserção dos dados quanto a situação do recurso, se bloqueado ou liberado, na tela de propostas cadastradas;
- Atualização da localização dos processos inseridos no SEI;
- Atualização dos dados referentes a habilitação, uma vez que o local da informação foi alterado;
- Inserção dos dados referentes as publicações no diário oficial para as propostas de convênio;
- Atualização do ano, lei e texto na tela de login.

## 1.0.4-rc.5 _(03/10/2017)_
- Ajustes para atender a demanda Redmine #11969

## 1.0.4-rc.2 _(02/09/2017)_

- Ajustes para atender a demanda Redmine #8241. **`improvement`**

## 1.0.4-rc.1 _(31/08/2017)_

- Ajustes para atender a demanda Redmine #8270. **`improvement`**


## 1.0.3 _(31/08/2017)_

- Ajustes para atender a demanda Redmine #12060. **`improvement`**

## 1.0.2 _(06/06/2017)_

- Congelando a versão 1.0.2-rc.1. **`package`**

## 1.0.2.rc.1 _(04/07/2017)_

- Removido o e-mail da Cristiane na lista de e-mail de DSV e HMG. **`debug`**
- Corrigida a consulta de publicação da tela de detalhamento de proposta. **`bugfix`**
- Adicionado os campos "Nº do Processo Pgto" e "Localização do Processo Pgto" na consulta de publicação da tela de detalhamento de proposta. **`bugfix`**
- Colocado o cache para a consulta de parlamentares (nos combos). **`improvement`**

## 1.0.1 _(20/06/2017)_

- Congelando a versão 1.0.1-rc.1. **`package`**

## 1.0.1-rc.1 _(20/06/2017)_

- Ajustando a configuração para autenticar no SCPA com a nova sigla do sistema. **`improvement`**

## 1.0.0 _(19/06/2017)_

- Alterando as configurações para o _deploy_ em produção usar o contexto "/"" e não o "/emendas". **`improvement`**
- Primeira versão da aplicação em produção. **`package`**

## 1.0.0-rc.54 _(13/06/2017)_

- Ajustes na consulta de pareceres no detalhamento da proposta. **`bugfix`**

## 1.0.0-rc.53 _(09/06/2017)_

- Adaptada a consulta de pareceres no detalhamento da proposta, adicionando a sigla e o telefone da área responsável. Conforme orientação do FNS. **`improvement`**

## 1.0.0-rc.52 _(08/06/2017)_

- Ajustada a consulta do relatório padrão. Conforme orientação do FNS. **`bugfix`**

## 1.0.0-rc.51 _(01/06/2017)_

- Ajustado para não retornar mais de um registro na visualização do parecer, do EUC 081. Estava causando erro inesperado na aplicação. **`bugfix`**
- Otimizada a consulta de pagamentos que estava demorando para retornar registro. **`bugfix`**
- Alterada o mapeamento da linha do tempo para as etapas "Em Pagamento" e "Pago". **`bugfix`**
- Adequado o texto da tela de login. **`bugfix`**

## 1.0.0-rc.50 _(23/05/2017)_

- Removido da exibição do relatório os registros de proposta que estão em rascunho, se não for do ano atual. **`bugfix`**
- Corrigida a quebra da linha do tempo da proposta no navegador Mozilla Firefox. **`bugfix`**

## 1.0.0-rc.49 _(18/05/2017)_

- Colocado o botão "Visualizar Relatório" do Relatório Padrão, abaixo do form (ano e parlamentar), alinhado à direita. **`improvement`**
- Ajustado o agrupamento da grid de pareceres no PDF. **`bugfix`**
- Ajustada a informação de valor empenhado da emenda do relatório padrão por parlamentar. **`bugfix`**
- Ajustado os registros de empenho na consulta do EUC 081. Conforme orientação do FNS. **`bugfix`**
- Ajustado a consulta do gráfico de beneficiários para não levar em consideração as indicações e sim a quantidade de CNPJ (gestor e parlamentar). **`bugfix`**
- Adicionado o e-mail de ANNA CAROLINA GEBRIM e ADRIANA LOUZEIRO DA SILVA para os ambientes de HMG e DSV. **`debug`**
- Refeita a consulta do relatório padrão. **`bugfix`**

## 1.0.0-rc.48 _(11/05/2017)_

- Ajustado para não trazer os registros cancelados na consulta de pagamentos do EUC 081. Conforme orientação do FNS. **`bugfix`**

## 1.0.0-rc.47 _(10/05/2017)_

- Ajustado para não quebrar o valor na tela de proposta para telas pequenas. **`bugfix`**
- Removida a cruz do SUS na linha do tempo. **`improvement`**
- Alterada a tela para mostrar os botões independentemente da linha do tempo ter carregado ou não. **`improvement`**
- Alterada a ordem das grids de pareceres de convênios para mostrar a de Mérito primeiro. **`improvement`**
- Fixada a velocidade da animação da linha do tempo em velocidade 3, independentemente da quantidade de etapas. **`improvement`**
- Ajustada a consulta de pareceres do detalhamento da proposta para o que foi informado pelo FNS. **`improvement`**

## 1.0.0-rc.46 _(09/05/2017)_

- Atualizado o componente `app-notify` para a versão 2.2.1. **`improvement`**
- Ajustado para não postar o número da proposta errado na grid de pagamentos no detalhamento da proposta. **`bugfix`**
- Alterada a obrigatóriedade de fonte Arial para SansSerif (igual aos demais) nos PDFs do EUC 081. **`improvement`**

## 1.0.0-rc.45 _(08/05/2017)_

- Colocado para trazer a primeira vez ordenado pela data de forma decrescente, na consulta de pareceres do detalhamento da proposta. **`bugfix`**
- Ajustada a query do gráfico de pagamento com o fragmento do VL_PAGO informado pelo pessoal do FNS. **`bugfix`**
- Alterado o incremento do intervalo da animação da linha do tempo. **`improvement`**
- Alterado no extrato para diminuir as fontes dos títulos em caixa alta. **`improvement`**

## 1.0.0-rc.44 _(27/04/2017)_

- Correções no 087. **`bugfix`**
- Adaptando o sistema para usar estrutura nova para vincular beneficiários com a emenda. **`improvement`**
- Removendo o e-mail na alteração do valor da indicação de beneficiário. **`improvement`**

## 1.0.0-rc.43 _(20/04/2017)_

- Colocado para fechar automaticamente em 10 segundos, as mensagens de notificação. **`improvement`**
- Correções do 081. **`bugfix`**
- Ajustado para salvar corretamenta a inversão de recurso na alteração do valor da indicação de beneficiário. **`bugfix`**
- Removido o do Gabriel na lista de e-mail de DSV e HMG. **`debug`**
- Envio de e-mail restabelecido na alteração do valor da indicação de beneficiário. **`bugfix`**
- Removida a regra de verificação se o beneficiário já possue proposta com indicação de objeto vinculada à emenda consultada, na hora de excluir um beneficiário e apresentada sempre bloqueando o botão de excluir. **`improvement`**

## 1.0.0-rc.42 _(17/04/2017)_

- Aumentada a velocidade da animação da linha do tempo da proposta. **`improvement`**
- Alterado para exibir a informação "Ação" na alteração da indicação de beneficiário. **`bugfix`**
- Ajustes no caso de uso 081. **`bugfix`**
- Atualizado o componente `app-notify` para a versão 2.2.0. **`improvement`**
- Colocado para não fechar as mensagens de notificação automaticamente. **`improvement`**
- Ajustes nos relatórios. **`bugfix`**

## 1.0.0-rc.41 _(13/07/2017)_

- Alteração dos rótulos "FAF - PAB/MAC" e "FAF - TED" para "PAB/MAC" e "TED". **`improvement`**
- Ajustado para deixar uma largura mínima na caixa de informações dos gráficos. **`improvement`**
- Alterada a quantidade mínima do gráfico de emendas de parlamentar. **`improvement`**

## 1.0.0-rc.40 _(12/07/2017)_

- Para aonde mostra o tipo de proposta (tela de listagem e detalhamento): Deixado com o campo original da tabela. Excessão dos convênios que foram traduzidos assim: `coTipoProposta = '356'`: CONTRATO DE REPASSE (`coModalidade = 1`: CONVÊNIO OBRA), `coTipoProposta = '352'`: CONVÊNIO, `coTipoProposta = '353'`: CONVÊNIO EQUIPAMENTO ou `coTipoProposta = '355'`: CONVÊNIO PRODUTO e para os demais o valor do campo `coTipoProposta`. **`improvement`**
- Corrigido problema ao clicar em "Parecer", "Publicação", "Empenho" ou "Pagamento" enquanto carregava a linha do tempo. **`bugfix`**
- Correção do relatório padrão. **`bugfix`**
- Realinhado os campos da tela de alteração de valor na indicação de beneficiário. **`improvement`**
- Corrigido problema de rota quando acessava o módulo proposta e depois voltava para o módulo relatórios. **`bugfix`**

## 1.0.0-rc.39 _(07/04/2017)_

- Alterada a posição do rótulo do eixo Y "Valor" dos gráficos. **`improvement`**

## 1.0.0-rc.38 _(06/04/2017)_

- Ajustado para não perder a tradução do dropdow das telas de relatório. **`bugfix`**
- Adicionado o e-mail da Sílvia para o ambiente de HMG e do Higor para DSV e HMG. **`debug`**
- Ajustes nos relatórios. **`bugfix`**
- Alterada a consulta do gráfico de proposta para trazer os contadores por tipo e por item. **`improvement`**
- Alterada a consulta do gráfico de pagamento para deixar com base na mesma regra do gráfico de empenho. **`bugfix`**
- Atualizado o componente `app-modal` para a versão 2.1.3. **`improvement`**
- Atualizado o componente `app-seguranca` para a versão 2.7.4. **`improvement`**

## 1.0.0-rc.37 _(21/03/2016)_

- Validando o campo parlamentar quando troca de perfil como ASS. **`bugfix`**
- Colocando para trazer a ultimpa opção da visão ou filtro parlamentar. **`improvement`**
- Alterado para "Selecione" no modal de selelçao de perfil. **`improvement`**

## 1.0.0-rc.36 _(16/03/2016)_

- Alterandoa animação da linha do tempo da proposta. **`improvement`**
- Adicionada a mensagem detalhando o critério da liberação nas notificações da tela inicial. **`improvement`**
- Corrigida a listagem de destinatários dos e-mails da indicação de beneficiário. **`bugfix`**
- Colocado para não listar registros repetidos na grid de lilberações. **`bugfix`**
- Arrumada a listagem dos anos e parlamentares, levando em consideração a vigência e se o registro está ativo, na hora de trocar o parlamentar do assessor. **`bugfix`**
- Colocado o botão "Visualizar Relatório" do Relatório Padrão, abaixo do form (ano e parlamentar), alinhado à direita. **`improvement`**

## 1.0.0-rc.35 _(13/03/2017)_

- Ajuste na consulta do gráfico de empenho. Usando a view materializada. **`bugfix`**
- Ajustes para atender o caso de uso 088. **`bugfix`**
- Alterado o cursor para pointer na troca da foto. **`improvement`**
- Colocado para ficar desabilitado os campos ano e parlamentar quando o filtro automático de GES e TEC estiver ativo.  **`improvement`**
- Alteração na aparencia e animação da cruz do SUS na linha do tempo. **`improvement`**
- Correção do problema ao trocar a senha no primeiro acesso que já estava logando. **`bugfix`**
- Corrigida a pesquisa de beneficiário para trazer os registros quando não informado o filtro. **`bugfix`**
- Arrumada a consulta que estava trazendo registros repetidos de notificação de liberação para o critério Emenda. **`bugfix`**

## 1.0.0-rc.34 _(07/03/2017)_

- Ajustes no gráfico de proposta. **`bugfix`**
- Correção ortográfica no texto de login. **`bugfix`**
- Ajustes na linha do tempo da proposta. **`bugfix`**
- Alinhando os campos e colocando o Valor utilizado na Proposta pelo Parlamentar no lugar do Valor de Repasse da tela de detalhamento da proposta. **`bugfix`**
- Adicionado o e-mail da Cristiane e removido o do Higor na lista de DSV e HMG. **`debug`**
- Melhoria na aparencia de "Nenhum Registro Encontrado" nas notificações da tela inicial. **`improvement`**
- Alterado para exibição de percentual no gráfico de pagamento. **`improvement`**

## 1.0.0-rc.33 _(23/02/2017)_

- Colocando os ajustes do PDF na tela de detalhar habilitação. **`improvement`**
- Ajustes no de/para do gráfico de proposta. **`bugfix`**
- Alterado para exibição de percentual no gráfico de empenho. **`improvement`**

## 1.0.0-rc.32 _(22/02/2017)_

- Incrementada a versão do componente `angular-dropdown-multiselect`. **`improvement`**
- Modificada as consultas do contador e gráfico de propostas. Adicionado o "Outros Tipos" para colocar os registros não mapeados. **`bugfix`**
- Modificado os pontos verticais (eixo Y) no gráfico de beneficiarios para ficar somente com números inteiros. **`improvement`**
- Ajustes no PDF do detalhar habilitação. **`improvement`**

## 1.0.0-rc.31 _(21/02/2017)_

- Voltado os campos para como estava no PDF do detalhar habilitação. **`improvement`**

## 1.0.0-rc.30 _(20/02/2017)_

- Correção nos casos de uso: 77 e 87. **`bugfix`**
- Aplicada a regra na autenticação que caso a pessoa tenha perfis de ANA, TEC ou outros e GES manter GES e caso não tenha GES e tenha TEC e outros manter TEC. **`bugfix`**
- Colocado para mostrar habilitado o campo Parlamentar, na tela de troca de perfil, só quando informar o ano. **`bugfix`**
- Corrigido a troca de ano do parlamentar logado. Que não estava mantendo o id do parlamentar correto. **`bugfix`**
- Colocado para carregar os anos corretos na troca de perfil, quando PAR ou ASS. **`bugfix`**
- Colocado para carregar os parlamentares corretos na troca de parlamentar quando logado como ASS. **`bugfix`**
- Movido os campos para direita no PDF do detalhar habilitação **`improvement`**

## 1.0.0-rc.29 _(16/02/2017)_

- Correção no caso de uso: 76. **`bugfix`**
- Ajustado o texto da tela de login. **`improvement`**
- Alteração de itens reportados na homologação do caso de uso 88. **`bugfix`**
- Colocado para "cachear" as chamadas JS e CSS com a versão da aplicação.  **`improvement`**
- 081 - Imprimir Informações Proposta. **`new feature`** **`bugfix`**

## 1.0.0-rc.28 _(14/02/2017)_

- Implementação de novo comportamento: Ao entrar na tela de Listagem de Beneficiários, trazer para a consulta os filtros passado na tela anterior de Consultar Emendas. **`new feature`**
- Colocado os _links_ na tela de login dos telefones de contato. **`bugfix`**

## 1.0.0-rc.27 _(14/02/2017)_

- Corrigido problema que ao recarregar a tela não estava trazendo as informações do campo Parlamentares em português. **`bugfix`**
- Correções nos casos de uso: 58 e 81. **`bugfix`**

## 1.0.0-rc.26 _(13/02/2017)_

- Adicionado o e-mail do Gabriel e removido o da Cristiane na lista de DSV e HMG. **`debug`**
- Correções nos casos de uso: 077. **`bugfix`**
- Corrigido o rótulo dos Informes na tela inicial. **`bugfix`**
- Diminuído o destaque dos contadores nas notificações da tela inicial. **`improvement`**
- Alterado para inativar por ano. Aplicada a mudança que teve impacto em todos os lugares que tem uso de parlamentar “ativo”. **`bugfix`**
- Deixado o gráfico de emendas com a largura das barras na proporção de 30%. **`improvement`**

## 1.0.0-rc.25 _(10/02/2017)_

- Corrigida a consulta que retorna os dados para o gráfico de empenho. **`bugfix`**
- Colocado o _hint_ na foto do parlamentar. **`improvement`**
- Colocado para remover os centavos, sem arredondar, nos gráficos. **`bugfix`**
- Atualizado o componente `app-mask` para a versão 2.2.4. **`improvement`**
- Correção gráfico proposta. Os valores das situações estavam carregando no gráfico de forma errônea.  **`bugfix`**
- Removido as quebras de linhas das SQLs para se adequear no **server-logs (Graylog)**. **`improvement`**
- Alterada a visão das Liberações do Sistema, Vigências de Acesso e Informes na tela inicial. **`improvement`**
- Aplicado para carregar a barra do governo primeiro do cache e depois de lá do brasil.gov.br. **`improvement`**
- Correções nos casos de uso: 077, 083 e 084. **`bugfix`**

## 1.0.0-rc.24 _(09/02/2017)_

- Validações dos campos do tipo e-mail. **`bugfix`**
- Corrigido os rótulos do gráfico de proposta. **`bugfix`**
- Ajustes na aparência das barras dos gráficos. **`improvement`**

## 1.0.0-rc.23 _(08/02/2017)_

- Adicionado o modal de confirmação na hora de alterar as informações do assessor no conceder acesso. **`improvement`**

## 1.0.0-rc.22 _(08/02/2017)_

- Arrumada, conforme documentação, as mensagens na hora de alterar a senha. **`bugfix`**
- Adicionado espaçamento na assinatura dos e-mails. **`improvement`**
- O sistema identifica que o telefone principal e o secundário são iguais e apresenta a mensagem correspondente, na tela de dados do usuário e ao conceder acesso. **`improvement`**

## 1.0.0-rc.21 _(08/02/2017)_

- Na tela de conceder acesso:
  + Colocado para travar o CPF ao editar um acessor. **`improvement`**
  + Colocado para postar o formulário ao clicar no `Enter` e não voltar para grid como estava antes. **`bugfix`**
  + Travado o campo CPF para edição. **`bugfix`**
  + Travado para sempre deixar marcado o "Visualizar" para o Nível de acesso. **`improvement`**
  + Deixado para a pesquisa de e-mail sem distinção de acentuação e capsulação da letra. **`bugfix`**
  + Colocado para consultar o nome após colocar o CPF. **`new feature`**
- Adicionado no layout os botões de tamanho de fonte e contraste. **`improvement`**

## 1.0.0-rc.20 _(07/02/2017)_

- Alterada a mensagem de conceder acesso. **`bugfix`**
- Colocado o combo com o ano para que o gestor troque a visão do ano nos gráficos. **`improvement`**
- Ajuste nos templates dos e-mails. **`improvement`**

## 1.0.0-rc.19 _(06/02/2017)_

- Colocado para exibir o cargo 'N/A' quando não for Deputado nem Senador, na tela inicial e nos dados do parlamentar. **`bugfix`**
- Correção do problema ao adicionar novo parlamentar. Agora levando em consideração a tabela `TB_ANO_PARLAMENTAR`. **`bugfix`**
- Correções no relatório personalizado. **`bugfix`**

## 1.0.0-rc.18 _(06/02/2017)_

- Da tela de conceder acesso:
  + Colocada as validações no campo data. **`bugfix`**
  + Colocada a mensagem “Confirma a exclusão? Sim ou Não“ na hora de exluir o registro. **`bugfix`**
  + Adequada as mensagens conforme documento. **`bugfix`**
  + Arrumado para recarregar os registros da _grid_ após voltar para a tela. **`bugfix`**
  + Ajustado o telefone na edição inicial, quando vem com o valor inválido. **`bugfix`**
  + Implementado para verificar o nome político no ano corrente quando for salvar um novo parlamentar. **`bugfix`**
  + Colocado para exibir o cargo 'N/A' quando não for Deputado nem Senador. **`bugfix`**
  + Implementada o envio da senha do novo parlamentar por e-mail. **`bugfix`**
- Da tela de pesquisa de emendas:
  + Situação Proposta. **`bugfix`**
  + Layout da tela. **`bugfix`**
- Correção de rótulo Ano/Exercício para Ano Exercício. **`bugfix`**
- Corrigido para exibir o e-mail na tela inicial de um parlamentar do ano corrente. **`bugfix`**
- Correção do caso de uso imprimir informações de proposta. **`bugfix`**
- Correção do nome do tipo da proposta (modalidade diferente de 1 e tipo da proposta igual a 356): "Contrato de Repasse" ou "Convênio Obra". **`bugfix`**
- Alterado os dados do campo "Cargo" conforme documentação. **`improvement`**
- Alterada a consulta de períodos, em Liberação Sistema e Notificações, para levar em consideração a hora, minuto e segundo igual a 23:59:59 no campo de data final. **`bugfix`**
- Ordenação de TODAS as _grids_ funcionando. **`bugfix`**

## 1.0.0-rc.17 _(02/02/2017)_

- Da tela que mantém os parlamentares:
  + Colocada a ordem inicial da listagem do histórico com as datas mais recentes no topo. **`improvement`**
  + Corrigido problema ao cancelar alteração (não confirmando) que o número de telefone não retornava para o cadastrado inicialmente.  **`bugfix`**
  + Colocado para listar somente os parlamentares do ano corrente. **`bugfix`**
  + Colocado para pesquisar o nome político com a regra geral de pesquisa. Ignorando acentuações e espaços no inicio e no fim do termo pesquisado. **`bugfix`**
  + Corrigido a instabilidade ao ativar/inativar o parlamentar que não atualizava a listagem. **`bugfix`**
  + Corrigida o carregamento do campo "Cargo". **`bugfix`**
  + Alterado o hint para "Alterar" do botão da _grid_. **`bugfix`**
  + Arrumada a validação do telefone. **`bugfix`**
- Ajuste para não adicionar fotos .gif. **`bugfix`**
- Ajustada a consulta que retorna as vigencias para considerar valores inteiros na quantidade de dias para expirar. **`bugfix`**
- Melhoria de desempenho. Elminando execução duplicado de consultas paginadas. **`bugfix`**
- Corrigido problema na hora de exibir o nome original do anexo da notificação na tela de edição. **`bugfix`**
- Corrigido um problema que ordenava de forma incorreta as grids que tem campo data. **`bugfix`**

## 1.0.0-rc.16 _(31/01/2017)_

- Alterando a configuração do SMTP de HMG e PRD. **`bugfix`**
- Adicionado o e-mail silvia.ibiapina@saude.gov.br para receber, enquanto homologação, os e-mail que o sistema enviar. **`debug`**
- Da tela que mantém os parlamentares:
  + Alterado os rótulos das opções "Bloquear" e "Liberar" para "Inativar" e "Ativar", respectivamente, na listagem principal. **`improvement`**
  + Alterado para persistir e exibir o nome do responsável ao invés do e-mail, no histórico. **`bugfix`**
  + Corrigido para a pesquisa ignorar acentuações. **`bugfix`**

## 1.0.0-rc.15 _(31/01/2017)_

- A proposta em Rascunho foi categorizada como “Em complementação” no gráfico (e contador) de Propostas. **`new feature`**
- 090 - Gerar Relatório Personalizado. **`new feature`** **`bugfix`**

## 1.0.0-rc.14 _(30/01/2017)_

- Correção da composição do recurso. **`bugfix`**
- Corrigida todas as consultas que trazia telefone com o caracteres que quebram a máscara na tela. **`bugfix`**
- Otimizada a consulta que atualizava os saldos da emenda. **`improvement`**
- Corrigido que não carregava os campos do parlamentar, quando logado como assessor. **`bugfix`**
- Incrementada a versão `datasus-arquivos-1.0.0` para `datasus-arquivos-1.1.0` **`improvement`**
- 089 - Visualizar Painel Controle. **`new feature`** **`bugfix`**

## 1.0.0-rc.13 _(27/01/2017)_

- Alterada a mensagem padrão de campo obrigatório que vem do `app-validator` **`bugfix`**
- 082 e 086: Ajuste na consulta de período, caso informado somente a data incial ou data final. **`improvement`**

## 1.0.0-rc.12 _(26/01/2017)_

- 082 - Manter Liberação do Sistema. **`new feature`** **`bugfix`**

## 1.0.0-rc.11 _(25/01/2017)_

- Otimização das consultas de habilitação. **`improvement`**
- Correções na tela que cadastra o assessor. **`bugfix`**
- Correções na tela que visualiza os dados do palamentar. **`bugfix`**
- Correções na tela do painel de controle, na parte de liberações exibia o texto de expiração de dias sem espaço. **`bugfix`**

## 1.0.0-rc.10 _(25/01/2017)_

- Removido o teste do NLS (api/v1/ms/parlamentares/?anoParlamentar=1). **`debug`**
- 082 - Manter Liberação do Sistema. **`new feature`** **`bugfix`**

## 1.0.0-rc.09 _(19/01/2017)_

- Correções na hora de colocar para não mostrar a foto e quando abrir como assessor que não carrega a foto. **`bugfix`**

## 1.0.0-rc.08

- Correções diversas após a alteração da estrutura dos dados do parlamentar no usuário logado. **`bugfix`**

## 1.0.0-rc.07

- Alterações no login. **`improvement`**

## 1.0.0-rc.06 _(17/01/2017)_

## 1.0.0-rc.05

- Teste do NLS (api/v1/ms/parlamentares/?anoParlamentar=1). **`debug`**
- 091 - Manter Foto Parlamentar. **`new feature`**
- 092 - Validar Foto Parlamentar. **`new feature`**

## 1.0.0-rc.04

- 076 - Manter Indicação Beneficiário. **`new feature`**
- 083 - Detalhar Habilitação. **`new feature`**
- 086 - Manter Notificação. **`new feature`**

## 1.0.0-rc.03

- 058 - Autenticar usuário. **`new feature`**
- 075 - Consultar Emenda. **`new feature`**
- 077 - Exibir Proposta. **`new feature`**
- 078 - Conceder acesso. **`new feature`**
- 079 - Detalhar proposta. **`new feature`**
- 080 - Alterar informações do usuário. **`new feature`**
- 084 - Detalhar beneficiário. **`new feature`**
- 085 - Controlar acesso parlamentar. **`new feature`**
- 088 - Escolher Perfil. **`new feature`**

---

## _Tags_ disponíveis

|_Tag_|Descrição|
|:-:|:--|
|**`improvement`**|Melhoria, implementação nova em cima de uma existente ou ajuste para melhorar algo.|
|**`bugfix`**|Correção de falha, erro ou coisa corriqueira.|
|**`new feature`**|Nova funcionalidade, recurso, caso de uso, etc.|
|**`debug`**|Inspecionamento de código, comportamento ou valores.|
|**`package`**|Fechamento de versão.|
