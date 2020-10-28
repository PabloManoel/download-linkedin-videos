# Download linkedIn videos

## Objetivos

- Criar um site que redirecione o usuário para a URL contendo o video do linkedin
- Nesse site haverá um tutorial de como fazer o download do video

## Passos

- ~~Criar uma pagina html~~
- ~~Criar um titulo, um input e um botao~~
- O botao acionará um script que:
  - Fará uma requisicao para a URL informada no input
  - Resgatará o html da URL informada
  - Pegará a tag video da URL informada
  - Pegará o atributo src da URL informada
  - imprimirá o resultado no console
  - após isso o script deverá redirecionar o visitante à URL do resultado

## Validações

- Validar retorno 200 da URL
- Validar que o site requisitado contem a tag video

## Aprendizados

- ```&amp;``` - Substitui & (e comercial) na url pois dependendo do que acompanha o & o caracter pode ser formatado com outro simbolo.
- ```&quot;``` - Substitui " (aspas) na url pois dependendo do que acompanha as aspas o caracter pode ser formatado com outro simbolo.
- ```Web Scraping``` - Tecnica que consiste em extrair informacoes relevantes de determinados sites para depois serem analisadas

## Links uetis

- Web Scraping com NodeJs: https://medium.com/@fabiojanio/node-js-web-scraping-com-puppeteer-29dd974eb042
- Web Scraping com NodeJs (2) : https://pusher.com/tutorials/web-scraper-node
- url video linkedin de exemplo: https://dms.licdn.com/playlist/C4D05AQGaEFrQWsbHpw/feedshare-ambry-analyzed_servable_progressive_video/0?e=1603940400&v=beta&t=_r3uhWaK6xYtrtVA3tnpNiDxs9ci9rVoIX7emGdfkag
- url post contendo video linkedin: https://www.linkedin.com/posts/ricardoamorimricam_mais-de-um-s%C3%A9culo-de-evolu%C3%A7%C3%A3o-dos-gastos-ugcPost-6724466845987942400-5ijy/
- CORS: https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Controle_Acesso_CORS