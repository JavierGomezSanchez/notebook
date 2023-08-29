# notebook


<h3>http methods</h3>
	<li>	post </li>
	<li>	get</li>
	<li>	head</li>
	<li>	options</li>
	<li>	delete</li>
	<li>	...</li>

<h3>XSS (Cross-Site scripting)</h3> 
Consiste en inyectar código malicioso en una web, existen 3 tipos:<br>
			<li>reflected </li>
			<li>stored</li>
			<li>dom	</li>
Para evitarlo:<br>
			<li>CSP headers</li>
			<li>HtppOnly headers</li>
			<li>Validate any app input</li>
			<li>Sanityze</li>

<h3>CRSF (Cross Site Request Forgery)</h3>
Un atacante induce a la victima a realizar acciones en una web que el realmente no desea (por ejemplo cambiar password)
<li>Uso de tokens</li>
<li>Cabecera HTTP</li>
Access-Control-Allow-Origin=http://yoursite.com
   
<h3>CORS (Cross-Origin Resource Sharing)</h3>
	Cargar contenido en una web de un servidor externo (diferente url, puerto o protocolo)
 
<h3>crypto</h3>
	<li>encryption vs encode (AES,RSA VS ASCII,BASE64)</li>
		encryption is more secure than encoded
		encryption has a key, encode are public algorithms
	<li>simetic encription vs asimetric </li>
	<li>tls </li>
