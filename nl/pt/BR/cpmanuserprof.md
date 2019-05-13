---

copyright:

  years: 1994, 2019

lastupdated: "2019-04-09"

keywords: user profile, administrative access, select account 

subcollection: customer-portal

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# Gerenciando um perfil do usuário
{: #customerportal_accuserprof}

No portal do cliente, um perfil do usuário tem vários dados sobre o usuário, incluindo informações de contato e a chave de API. Também é o local no qual as senhas são armazenadas. Se você tiver acesso administrativo, será possível mudar as permissões e o acesso ao dispositivo por meio do perfil.
{:shortdesc}

No perfil do usuário, é possível gerenciar informações de contato e senhas, visualizar chaves API e atualizar permissões e acesso ao dispositivo com base em suas permissões.

## Editando um perfil de usuário
{: #cp_edituserprofile}

Depois que um perfil do usuário é criado no portal do cliente, é possível editá-lo a qualquer momento. Os detalhes associados ao perfil do usuário incluem informações pessoais, configurações de login, detalhes de acesso da API, assinaturas de notificação do usuário e perguntas de segurança. Use as etapas a seguir para editar um perfil do usuário.

1. Acesse o portal do cliente usando as suas credenciais exclusivas.
2. Selecione **Conta > Usuários** na barra de navegação.
3. Clique no nome do usuário para acessar o perfil do usuário associado para ele.
4. Edite os detalhes de **Perfil do usuário** conforme necessário. Para usuários em contas que usam IBMid para autenticação, atualize seu e-mail e senha em seu perfil do IBMid. Consulte a Tabela 1 para obter mais informações.
5. Se desejar reconfigurar sua senha depois de efetuar login, clique em **Reconfigurar senha** para gerar um e-mail que permita mudar sua senha.
6. Clique em **Editar usuário** para enviar as mudanças.

| Campo | Definição |
|-----|----------|
| Nome, sobrenome | Nome e sobrenome do usuário que está associado ao perfil do usuário.|
| Endereço de e-mail | Endereço de e-mail preferencial para receber notificações da infraestrutura do {{site.data.keyword.BluSoftlayer_notm}} sobre a conta. Mudar o endereço de e-mail muda o registro na infraestrutura do {{site.data.keyword.BluSoftlayer_notm}}. Essa mudança não afeta a ligação com as credenciais de autenticação do IBMid. Deve-se mudar o endereço de e-mail para o IBMid no perfil do IBMid.|
| Fuso horário | Fuso horário preferencial a ser usado ao exibir dados com registro de data e hora.|
| Telefone, telefone alternativo| Números de telefone de contato preferenciais a serem usados pela infraestrutura do {{site.data.keyword.BluSoftlayer_notm}}.|
| Endereço, cidade, país, estado/município, CEP | Endereço completo para contato a ser usado pela infraestrutura do {{site.data.keyword.BluSoftlayer_notm}}.|
{: caption="Tabela 1. Definições de configuração de informações pessoais para editar um perfil do usuário" caption-side="top"}

|Campo|Definição|
|-----|----------|
| Acesso restrito ao IP | Endereço IP ao qual restringir o acesso ao tentar usar o portal do cliente sob o perfil de usuário associado. |
| Expiração de senha em (apenas para usuários em contas que NÃO usam IBMid para autenticação) | Quantidade de tempo em que uma senha deve estar associada ao perfil do usuário antes que uma nova senha precise ser selecionada. |
| Usuário pai | Conta do usuário que é considerada o usuário pai do perfil do usuário. O padrão do usuário pai é o ID da conta principal. |
| Requer perguntas de segurança? | Selecione essa caixa de seleção quando perguntas de segurança devem ser requeridas durante o login. Se essa caixa estiver selecionada, perguntas de segurança serão requeridas para o perfil do usuário. |
| Senha da VPN | Senha a ser usada para acesso à VPN. Clique na caixa de seleção **Usar senha do portal para a VPN** para usar a senha do portal do cliente para acessar a rede de infraestrutura do {{site.data.keyword.BluSoftlayer_notm}} por meio da VPN. |
{: caption="Tabela 2. Definições de configuração de login para editar um perfil do usuário" caption-side="top"}

|Seção|Campo|Definição|
|-------|-----|----------|
| Informações de acesso à API | IPs permitidos | Endereços IP permitidos para se autenticar à API com a chave API exclusiva associada ao perfil do usuário |
| Assinaturas de notificação do usuário | Faturamento | Marque a caixa de seleção **Faturamento** para receber uma fatura de e-mail após sua criação. |
| Perguntas de segurança | Pergunta de segurança | Ao editar seu perfil, essa é a pergunta que deve ser respondida para efetuar login quando perguntas de segurança são ativadas para seu perfil.
| Respostas de segurança | Resposta | Resposta com distinção entre maiúsculas e minúsculas para a pergunta de segurança aplicável. |
{: caption="Tabela 3. Outras definições de configuração para editar um perfil do usuário" caption-side="top"}
Depois de enviar edições para um perfil do usuário, as mudanças são aplicadas imediatamente. É possível mudar o perfil do usuário novamente a qualquer momento repetindo as etapas anteriores.

Consulte [Alternando para IBMid](/docs/account?topic=account-unifyingaccounts#switchtoIBMid) para obter mais informações sobre como configurar uma conta do IBMid.

## Editando permissões do portal do cliente de um usuário
{: #cp_editusercpperm}

As permissões de usuário no portal do cliente são configuradas pelo administrador de conta quando o usuário é incluído e podem ser editadas a qualquer momento por um usuário autorizado. É possível editar o seu próprio perfil de usuário e, se você for um usuário administrativo, alguns campos dos perfis de usuário para usuários que você incluiu. As permissões são divididas em cinco guias: suporte, dispositivos, rede, serviços e conta. É possível atualizar as permissões para um usuário de cada vez e deve-se salvar as mudanças para que se tornem ativas.

Use as etapas a seguir para editar permissões do portal do cliente de um usuário.

1. Acesse o portal do cliente usando as suas credenciais exclusivas.
2. Selecione **Conta > Usuários** na barra de navegação.
3. Clique no nome do usuário para acessar o perfil do usuário.
4. Clique no ícone **Permissões** para acessar a janela Permissões.

  É possível obter uma mensagem indicando que as mudanças não foram salvas no perfil do usuário. Se nenhuma mudança foi feita no perfil, clique para descartar as mudanças e acesse a janela Permissões.
  {: tip}

5. Selecione as permissões:
  * Para configurar permissões rápidas, selecione o conjunto de permissões na lista **Permissões rápidas**. Depois de selecionar um conjunto de permissões, cada permissão associada ao conjunto é exibida em texto laranja com uma seta laranja apontando para a caixa de seleção. Em seguida, clique em **Configurar permissões** para cada guia.
  * Para configurar permissões individuais, selecione ou cancele a seleção de cada caixa de seleção nas guias para atualizar as permissões do usuário. Clique em **Selecionar todas as permissões** ou **Cancelar seleção de todas as permissões** em qualquer guia para selecionar ou cancelar a seleção de todas as permissões de uma vez.
6. Clique em **Editar permissões do portal** para enviar mudanças e atualizar as permissões do usuário.
7. Para reconfigurar as permissões do usuário para as configurações originais em vez de salvá-las, clique em **Reconfigurar permissões**. Clique em **Cancelar** para cancelar as mudanças e retornar à janela Usuários.

As permissões de usuário são atualizadas imediatamente após você enviar as mudanças. Se permissões tiverem sido concedidas, o usuário poderá visualizar ou interagir com os recursos selecionados. Se as permissões tiverem sido removidas, o usuário não poderá visualizar ou interagir com os recursos selecionados. As permissões poderão ser atualizadas novamente a qualquer momento repetindo as etapas anteriores.

## Incluindo autenticação externa para um usuário
{: #cp_addextauthuser}

No portal do cliente, é possível ativar a autenticação externa de dois fatores (2FA) para incluir proteção quando você efetuar login no portal. Essa camada extra de segurança protege a conta contra acesso não verificado, assegurando que dispositivos, dados e informações de conta sejam protegidos. Consulte [Configurando a autenticação de dois fatores](/docs/customer-portal?topic=customer-portal-cp_setup-2fa#cp_setup-2fa) para obter mais informações.


## Mudando o status de um usuário
{: #cp_changeuserstat}

Seu status no portal do cliente determina sua acessibilidade ao portal do cliente. As categorias de status que você pode atualizar na conta incluem Ativo, Desativado e Somente VPN. Seu status pode mudar por vários motivos e pode ser atualizado a qualquer momento. As categorias de status do cliente incluem aquelas que os usuários podem atualizar e aquelas que são atualizadas automaticamente. Elas incluem:
<dl>
<dt>Ativo</dt>
<dd>O usuário tem acesso total ao portal do cliente e à VPN com base em permissões que são configuradas pelo administrador da conta. Esse status pode ser selecionado manualmente ou mudado a qualquer momento.</dd>
<dt>Desativado</dt>
<dd>O usuário não tem acesso a nenhuma permissão ou assinatura na conta, incluindo o portal do cliente e a VPN. Se a categoria de status é configurada como desativado por outro usuário na conta, esse status pode ser selecionado ou mudado manualmente a qualquer momento.</dd>
<dt>Somente VPN</dt>
<dd>O usuário tem acesso total à conectividade da VPN, com base em seu conjunto de permissões, mas não pode acessar o portal do cliente. Esse status pode ser selecionado ou mudado manualmente a qualquer momento.</dd>
<dt>Inativo</dt>
<dd>O usuário não acessou o portal do cliente ou a VPN nos últimos 60 dias. Este é um status gerado pelo sistema.</dd>
<dt>cancel_pending</dt>
<dd>Um administrador na conta cancelou esse usuário e o cancelamento está sendo processado. Este é um status gerado pelo sistema.</dd>
</dl>

Use as etapas a seguir para mudar o status de um usuário no portal do cliente.

1. Acesse o portal do cliente usando as suas credenciais exclusivas.
2. Selecione **Conta** > **Usuários** na barra de navegação.
3. Selecione **Mudar o status do usuário** na lista **Ações**.
4. Na lista **Status**, selecione o status apropriado de acordo com as definições na lista anterior.
5. Clique em **Salvar**.

Depois de atualizar o status de um usuário, as mudanças na acessibilidade do portal do cliente são alinhadas ao novo status.


## Editando o acesso de um usuário à VPN
{: #cp_edituservpnaccess}

Quando um [novo usuário é incluído](/docs/customer-portal?topic=customer-portal-customerportal_addusertocpacct#customerportal_addusertocpacct) em uma conta do portal do cliente, o acesso à VPN é selecionado por meio de vários métodos de conexão, incluindo SSL, PPTP ou uma combinação dos dois. Com o acesso à VPN, a rede privada pode ser acessada em sua totalidade ou o acesso à rede pode ser limitado a uma ou mais sub-redes específicas. É possível gerenciar e atualizar o acesso à VPN a qualquer momento na janela Usuários. Use as etapas a seguir para editar o acesso de um usuário à VPN.

1. Acesse o portal do cliente usando as suas credenciais exclusivas.
2. Selecione **Conta** > **Acesso à VPN** na barra de navegação.
3. Na coluna **Acesso à VPN** para o usuário, clique no link de tipo de acesso VPN atual para exibir a janela Acesso à VPN.
4. Na lista de **Tipos de VPN**, selecione um método de VPN (SSL, PPTP, SSL e PPTP ou nenhum) para designar o usuário.
5. Indique como você deseja gerenciar o **Acesso à sub-rede**:
  * Selecione **Automático** para gerenciar automaticamente o acesso à sub-rede.
  * Selecione **Manual** para gerenciar manualmente o acesso à sub-rede e, em seguida, marque a caixa de seleção **Conceder acesso** para cada sub-rede à qual você deseja que o usuário tenha acesso. Certifique-se de limpar todas as caixas de seleção de sub-redes que você não deseja que o usuário acesse.
6. Clique em **Salvar**.

Depois de atualizar o acesso à VPN de um usuário, suas permissões serão atualizadas e a coluna Acesso à VPN exibirá o método de acesso à VPN atualizado, se aplicável.

### Ativando ou desativando o acesso à VPN
{: #cp_pptpvpn}

É possível ativar a VPN PPTP para formar um túnel seguro para a rede privada da infraestrutura do {{site.data.keyword.BluSoftlayer_full}} que usa o software cliente especializado executado em sua área de trabalho ou dispositivo dedicado. Será possível usar PPTP se você precisar conectar seu escritório inteiro ou se não puder usar a solução VPN SSL.

É atribuída uma conexão PPTP com conexões extras disponíveis a você. É possível solicitar suporte para ativar o acesso ilimitado ao PPTP, disponível sem encargos extras. Use as etapas a seguir para ativar ou desativar o acesso à VPN PPTP:

1. Acesse o portal do cliente usando as suas credenciais exclusivas.
2. Selecione **Conta** > **Acesso à VPN** na barra de menus.
3. Na coluna **Acesso à VPN** para o usuário, clique no link de tipo de acesso VPN atual para exibir a janela Acesso à VPN.
4. Na lista de **Tipos de VPN**, selecione um método de VPN (SSL, PPTP, SSL e PPTP ou nenhum) para designar o usuário.


## Selecionando notificações por e-mail
{: #cp_select-email-notifications}

É possível selecionar quais notificações de e-mail que você deseja receber da
infraestrutura do {{site.data.keyword.BluSoftlayer_notm}} e quais você não deseja receber. Por padrão,
você recebe todas as notificações por e-mail, mas é possível mudá-las a qualquer momento. Para mudar suas
configurações de notificação por e-mail, use as etapas a seguir:
1. Acesse o portal do cliente usando suas credenciais exclusivas para a conta que está associada ao endereço de e-mail que recebe notificações.
2. Clique em **Conta** > **Usuários** > **Preferências
de e-mail** na barra de menus.
3. Na lista de tipos de notificação, limpe as notificações que não deseja mais receber.

Suas mudanças são salvas automaticamente. Essas configurações afetam os e-mails enviados a você, no entanto, eles não afetam as notificações por e-mail de nenhum outro usuário de sua conta.


## Configurando a opção Suportado pela União Europeia
{: #cp_seteusupported}

É possível indicar que você deseja suporte exclusivamente de uma equipe de suporte que está localizada fisicamente na União Europeia (UE). É possível selecionar essa opção ao configurar sua conta ou ao atualizar sua conta existente. Para configurar a opção **Suportado pela União Europeia**, use as etapas a seguir:
1. Acesse o portal do cliente usando as suas credenciais exclusivas.
2. Clique em **Conta** > **Gerenciar** > **Perfil da Empresa** na barra de menus.
3. Selecione a caixa de seleção **Suportado pela União Europeia**.
4. Clique em **Solicitar atualização de perfil**.

Caso a opção **Suportado pela União Europeia** não esteja disponível, é possível que você tenha usuários em sua conta com o acesso à VPN PPTP ativado. Para ativar a opção **Suportado pela União Europeia**, primeiro desative o acesso à VPN PPTP para todos os usuários em sua conta. Para obter mais informações, veja [Ativando ou desativando o acesso à VPN PPTP](/docs/customer-portal?topic=customer-portal-cp_pptpvpn#cp_pptpvpn).

Para obter mais informações sobre como implementar a opção **Suportado pela União Europeia** ao abrir um chamado de suporte, consulte [Solicitando suporte para recursos na União Europeia](/docs/get-support?topic=get-support-getting-customer-support#eusupportedservices).
