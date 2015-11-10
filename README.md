# NFS-e Lajeado
<b>WSDL - Web Services Description Language</b>
 
  A seguir são apresentados os links para acesso das descrições dos serviços, especificações de acesso e métodos disponíveis da integração via Web Service da NFS-e. O acesso pode ser feito na base de homologação para fins de testes e na base produção que emitirá a nota fiscal com efeitos legais. Os testes ou emissão da NFS-e só poderão ser efetuados após autorização do CNPJ do contribuinte e com a utilização do e-CNPJ.

WSDL Homologação
WSDL Produção

<b>Arquivo XSD e exemplos de .XML: </b>
<ul>
	<li>
		<a href="https://wiki.thema.inf.br/wiki/help/xmlRemessaNfse">XML Remessa NFS-e</a>
	</li>
	<li>
		<a href="https://wiki.thema.inf.br/wiki/help/xmlCancelamento">XML Cancelamento de NFS-e</a>
	</li>
	<li>
		<a href="https://wiki.thema.inf.br/wiki/help/consultarSituacaoLoteRps">XML Consulta Situação do Lote</a>
	</li>
	<li>
		<a href="https://wiki.thema.inf.br/wiki/help/consultarLoteRps">XML Consulta Lote</a>
	</li>
	<li>
		<a href="https://wiki.thema.inf.br/wiki/help/consultarNfse">XML Consulta NFS-e</a>
	</li>
	<li>
		<a href="https://wiki.thema.inf.br/wiki/help/consultarNfsePorRps">XML Consulta NFS-e por RPS</a>
	</li>
</ul>

<b>Programa de validação do .xml (NFSe): </b>

  Abaixo está disponibilizado o programa para validação do arquivo .xml de remessa. Este programa tem por finalidade auxiliar na identificação de problemas com as tags. Caso acuse erro de ID nas tags LoteRps id="LOTE1234" ou InfRps id="RPS12345", basta remover os dados deixando apenas LoteRps e InfRps. Após o upload e validação, será exibida na tela qual tag apresenta inconsistência, devendo ser ajustada seguindo as informações do manual e o formato de dados encontrado no arquivo .xsd. Se estiver tudo correto, será exibida a mensagem informando que o .xml está ok.

<ul>
	<li>
		<a href="https://grp.lajeado.rs.gov.br/erp/acessoexterno/programaAcessoExterno.faces?codigo=670195">Validador de .xml</a>
	</li>
</ul>
