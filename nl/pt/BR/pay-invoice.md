---

copyright:

  years: 1994, 2019

lastupdated: "2019-01-28"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:note: .note}
{:screen: .screen}
{:new_window: target="_blank"}


# Fazendo um pagamento
{: #customerportal_makepayment}

Todos os detalhes de faturamento da infraestrutura do {{site.data.keyword.Bluemix}}, desde faturas até informações de pagamento, são armazenados com segurança no portal do cliente. Se seu método de pagamento mudar ou seu cartão de crédito for cancelado ou expirar, atualize suas informações de pagamento para evitar encargos de atraso.
{:shortdesc}

## Visualizando sua fatura
{: #cp_viewinvoice}

Na janela Faturas, cada fatura individual é resumida pelo número da fatura, data, tipo de fatura e vários saldos monetários. As faturas podem ser qualquer um dos tipos a seguir:

<dl>
<dt>Nova</dt>
<dd>A primeira fatura em uma série de faturas recorrentes.</dd>
<dt>Recorrente</dt>
<dd>Uma fatura para encargos contínuos que estão ativos na conta há mais de um mês.</dd>
<dt>Encargo único</dt>
<dd>Uma tarifa única para várias despesas, podendo incluir excedentes.</dd>
<dt>Crédito</dt>
<dd>Um crédito da infraestrutura do {{site.data.keyword.BluSoftlayer_notm}} para o saldo da conta.</dd>
<dt>Reembolso</dt>
<dd>Uma reversão de encargos, para um encargo único ou contínuo.</dd>
</dl>

Também é possível visualizar um resumo de faturamento para a conta, incluindo as informações a seguir:
  * Saldo atual e próximo saldo estimado
  * Método de pagamento
  * Últimas e próximas datas de fatura recorrente

1. Clique em **Conta** > **Faturamento** > **Faturas** no menu.
2. É possível visualizar a fatura no portal do cliente ou fazer download da fatura.

Se você estiver visualizando a fatura no portal do cliente, uma lista detalhada de itens de faturamento será mostrada para a fatura selecionada. Clique em qualquer lugar na linha de um item de faturamento para visualizar mais detalhes divididos em itens sobre a cobrança. Se você transferiu a fatura por download, será possível visualizá-la com base em suas configurações do navegador. As faturas transferidas por download fornecem um resumo detalhado e o faturamento detalhado em itens para cada item de faturamento.

Se você estiver localizado fora dos Estados Unidos, use uma ferramenta chamada [Invoices](http://www.ibm.com/support/customer/invoices){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo") para visualizar suas faturas. As etapas específicas para cada país são listadas em [https://www.ibm.com/support/customer/zz/en/selectcountrylang_invoices.html](https://www.ibm.com/support/customer/zz/en/selectcountrylang_invoices.html){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo"). Se você tiver algum problema, entre em contato conosco em 1-866-325-0045 e solicite acesso à sua fatura.
{: note}

## Incluindo um método de pagamento
{: #cp_cpmanacctbillpay}

Cada conta do SoftLayer precisa ter um cartão de crédito no arquivo que é cobrado automaticamente pela quantia da fatura de cada mês. Essas informações devem estar sempre atualizadas para evitar pagamentos atrasados. É possível atualizá-las a qualquer momento para assegurar que as informações de pagamento estejam sempre precisas. Se as informações de cartão de crédito no arquivo estiverem corretas, mas você desejar aplicar uma forma alternativa de pagamento para o saldo atual, consulte [Gerenciando seus itens de faturamento](/docs/customer-portal/cpmanacctbillpay.html#cp_makeonetimepayment). Use as etapas a seguir para incluir um método de pagamento para uma conta no portal do cliente.

1. Clique em **Conta** > **Faturamento** > **Método de pagamento** no menu.
2. Insira os detalhes de faturamento necessários para o cartão em cada campo na seção **Endereço para cobrança**.
> **Nota:** clique na caixa de seleção **Usar informações da empresa** para preencher automaticamente os campos com as informações da empresa que a infraestrutura do {{site.data.keyword.BluSoftlayer_notm}} possui no arquivo para a conta.
3. Insira as informações do cartão de crédito em cada campo na seção **Informações de pagamento**.
4. Clique em **Incluir cartão de crédito** para incluir o cartão de crédito como um método de pagamento mensal.
5. Opcionalmente, selecione **Suportado na EU** para assegurar que a equipe de suporte na Europa lida com os seus problemas de manutenção e suporte.  Para obter mais informações sobre essa opção, consulte [Configurando a opção europeia suportada](/docs/customer-portal/cpmanuserprof.html#cp_seteusupported).

Após você incluir o método de pagamento, a solicitação será processada pelos representantes de conta SoftLayer para assegurar a validade do cartão. Os cartões validados ficam disponíveis para uso na conta dentro de 24 horas. A mudança de status para o método de pagamento é enviada por e-mail para o contato que foi fornecido quando o método de pagamento foi incluído.

## Fazendo um pagamento único
{: #cp_makeonetimepayment}

É possível fazer pagamentos únicos usando uma conta do PayPal ou um cartão de crédito principal e é possível fazer pagamentos para um saldo total ou parcial. Os detalhes do pagamento único não são registrados para uso futuro e não modificam os métodos atuais de pagamento mensal da conta.

1. Acesse a página Fazer um pagamento único no portal do cliente.
 * No menu: acesse **Conta** > **Fazer um pagamento**.
 * Na página Faturas: clique em **Pagar saldo**.
2. Insira a quantia de pagamento no campo **Quantia de pagamento**.
3. Se você estiver fazendo seu pagamento com PayPal, clique em **PayPal** e siga os prompts do PayPal para concluir o pagamento. Nenhuma ação adicional é necessária. Se você estiver fazendo seu pagamento com um cartão de crédito, insira o **Número do cartão, a Expiração e o Código de segurança** nos campos apropriados.
4. Insira as informações de faturamento nos campos apropriados na seção **Endereço para cobrança do cartão de crédito**.
5. Opcionalmente, selecione **Suportado na EU** para assegurar que a equipe de suporte na Europa lida com os seus problemas de manutenção e suporte.  Para obter mais informações sobre essa opção, consulte [Configurando a opção europeia suportada](/docs/customer-portal/cpmanuserprof.html#cp_seteusupported).
6. Clique em **Pagar com cartão de crédito** para iniciar o pagamento.

Após iniciar o pagamento, o pagamento será processado. Se surgirem problemas com o pagamento, siga os prompts da infraestrutura do {{site.data.keyword.BluSoftlayer_notm}} ou do PayPal até que o problema seja resolvido. O pagamento será processado. A quantia é aplicada e o saldo atual é atualizado.
