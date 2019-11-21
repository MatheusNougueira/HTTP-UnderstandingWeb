<!DOCTYPE html>

<h1>HTTP-UnderstandingWeb</h1>

<h3>O que é o HTTP?</h3>
<p>O HTTP é um protocolo que define as regras de comunicação entre cliente e servidor na internet.</p>

<h3>O papel do HTTP entre o cliente e servidor</h3>
<p>Ele é responsável por definir a forma de como os dados são trafegados na rede através de várias regras.</p>

<h3>HTTPS – A versão segura do HTTP</h3>
<p>HTTPS, que basicamente é o HTTP comum, porém com uma camada adicional de segurança/criptografia que antes era SSL, mas posteriormente passou a ser também TLS. É muito comum que estas duas siglas sejam encontradas juntas como SSL/TLS por se tratarem da mesma questão de segurança. Sendo assim, temos dois termos:</p>
<ul>
  <li>HTTP: HyperText Transfer Protocol</li>
  <li>SSL/TLS: Secure Sockets Layer / Transport Layer Security</li>
</ul>

<h3>Funcionamento do HTTPS</h3>
<p>O HTTPS para garantir segurança usa criptografia baseada em chaves públicas e privadas e para gerar essas chaves públicas e privadas é preciso garantir a identidade de quem possui essas chaves e isso é feito a partir de um certificado digital, ou seja, um certificado digital é utilizado para identificar determinada entidade e ainda é utilizada para geração das chaves de criptografia.</p>

<h3>Características do HTTPS:</h3
<ul>
  <li>A chave privada fica apenas no lado do servidor - Exato, a chave privada é utilizada para descriptografar os dados que foram criptografados com a chave pública, por isso ela é importante e deve ficar apenas em posse do servidor;</li>
  <li>O certificado prova a identidade e tem validade - Correto, todo certificado tem uma data validade e serve para provar a identidade entre o cliente e o servidor;</li>
  <li>O certificado guarda a chave pública - Perfeito, é no certificado digital que encontramos a chave pública utilizada para criptografar os nossos dados.</li>
</ul>
<h4>Lembrando o HTTP não utiliza criptografia nenhuma e é inseguro! Para deixar a web segura devemos usar o HTTPS sempre.</h4>

<h3>As chaves do HTTPS</h3>
<p>HTTPS usa uma chave pública e uma chave privada.</p>
<p>As chaves estão ligadas matematicamente, o que foi cifrado pela chave pública só pode ser decifrado pela chave privada.</p>
<p>Isso garante que os dados cifrados pelo navegador (chave pública) só podem ser lidos pelo servidor (chave privada).</p>

<h3>URI ou URL?</h3>
<ul>
  <li>URI (Uniform Resource Identifier) - Identificador de Recurso Uniforme</li>
  <li>URL (Uniform Resource Locator) - Localizador padrão de recursos</li>
</ul>

<h3>Códigos de resposta HTTP</h3>
<p>No dia a dia os códigos 200, 404 e 500 são os mais utilizados</p>
<ul>
  <li>2xx significa coisa boa, a requisição foi executada com sucesso;</li>
  <li>3xx normalmente significa que o navegador precisa fazer algo a mais (o cliente precisa agir) pois algo mudou ou um recurso não existe mais;</li>
  <li>4xx significa que o navegador enviou dados errados, como por exemplo uma URL errada;</li>
  <li>5xx caso o servidor gere algum problema.</li>
</ul>

<h3>Métodos HTTP</h3>
<p>GET e POST são os dois mais utilizados na grande maioria das aplicações web.<p>
 <ul>
   <li>GET - recupera informações sobre o recurso identificado pela URI;</li>
   <li>POST - adiciona informações usando o recurso da URI passada;</li>
   <li>PUT - adiciona (ou modifica) um recurso na URI passada;</li>
   <li>DELETE - remove o recurso representado pela URI passada.</li>
</ul>
