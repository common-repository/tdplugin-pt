=== TradeDoubler PT ===
Contributors: sergio.martinez
Tags: tdplugin,tdplugin-pt,tradedoubler,td,affiliate,afiliados
Requires at least: 2.0.2
Tested up to: 2.8
Stable tag: trunk

Facilita a publicação para afiliados.

== Description ==

O plugin servirá para a publicação automática de pools com anúncios. Funciona realizando uma busca mediante determinadas palavras chave 

de produtos em quais o afiliado está inscrito, publicando-os automáticamente com dois estilos diferentes, mantendo o tracking de afiliado.


No campo de texto para publicar deveremos introduzir:

[td tdquery="a tua password" tdno="20" tdpg="0" tdmid="12345,234,189" tdcat="68" tdprice="20_200" td_estilo="1 o 2" prodfila="2"]

Onde:

-	Tdquery: palavras chave sobre as quais faremos a busca
-	Tdno: número de resultados que queremos mostrar
-	Tdpg:o número sobre o qual gostaríamos que se comece a mostrar
-	Tdmid: a identificação do comerciante, se são vários separados por vírgulas. 
-	Tdcat: a categoria sobre a qual realizar a busca
-	Td_estilo:de momento existem 2 estilos de apresentação:
o	1: O primeiro permite seleccionar ao usuário quantos resultados mostrar por filas mediante a variável de argumento “prodFila”.
o	2: O segundo mostrará um resultado por fila ocupando praticamente a largura da página
-	prodFila: permitirá ao usuário seleccionar o número de resultados a mostrar por casa fila.

== Installation ==

Terá que aceder ao menu “Settings/TradeDoubler XML Wordpress Plugin”, onde deveremos introduzir o nosso id de afiliado e o tempo que
residirão os ficheiros XML resultado das nossas buscas na memória cache do servidor onde tenhamos hospedada a nossa página web.

== Changelog ==

= 1.0 =
* Primera Version del plugin

== Arbitrary section ==

Para mais informação visite http://tdblog.es/
