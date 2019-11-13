# OpenCv Js

Exemplo simples de utilização do OpenCV no  navegador utilizado Javascript.

existem dois modos de instalar opencv Js.

- compilar o código fonte: [Build OpencvJS](https://docs.opencv.org/3.4/d4/da1/tutorial_js_setup.html) (Só os fortes conseguem)

- Também pode baixar o arquivo: https://docs.opencv.org/4.1.2/opencv.js  e importa-lo.

para executar o exemplo:

```zsh
git clone https://github.com/samuel-cavalcanti/opencvJs.git

http-server # https://www.npmjs.com/package/http-server
```

como podemos ver  no index.html: 
```html
 <input type="file" id="file_input" accept=".mkv">
```
os únicos arquivos de vídeo que são possíveis de abir são os do formato __mkv__. Possa ser que outros formatos também seja suportado, mas pelo que eu testei só o __mkv__ funcionou.  

Sinta-se a vontade a testar novos formatos de vídeo e me contar suas experiências.  
Caso queria  :)  