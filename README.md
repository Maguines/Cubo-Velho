# Cubo Velho
==============================================================================

Cubo Velho é um simulador de jogo da velha 3D (Qubik) escrito em javascript com a API de WebGL a partir da biblioteca Three.js.

Além da parte gráfica, também está presente o Algoritmo de Inteligência Artificial de Mínimo e Máximo (Minimax) em Python 3.6, que desafia o jogador humano ao tentar vencer.


### Como executar

O arquivo index.html deve ser aberto em um navegador Firefox se o arquivo for aberto localmente, pois o Chrome não permite requisições XMLHttp localmente.
Em um servidor, o jogo roda em qualquer navegador moderno que suporte WebGL.


### Arquivos

- "index.html"
Possui o corpo HTML do jogo, assim como o estilo da página e o script principal do jogo.

- "app.json"
Possui todos os objetos 3D da cena do jogo estruturados em formato JSON.

- Pasta "js"
Possui o códido minificado da biblioteca Three.js, o código principal do jogo e das câmeras que serão implementadas no jogo.


==============================================================================

O Jogo ainda está em desenvolvimento, e as partes gráficas e de inteligência ainda não estão integradas entre si.
