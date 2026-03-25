# Quais são as diferenças dos códigos?

## As diferenças
Primeiramente, é legal deixar claro que o meu código ficou diferente do código final do professor porque eu segui o que estava no enunciado e o código do professor tem coisas a mais

O CSS que o professor apresentou no final acabou ganhando algumas propriedades a mais para deixar o layout mais bonito, mas que não estavam nas instruções originais da tarefa. Abaixo eu explico o que o meu não tem (porque não foi pedido, rs) e o que essas propriedades extras fazem na prática:

---

## 1. A classe `.card`
No desafio, a instrução era colocar só cor de fundo, borda arredondada e largura. Foi exatamente o que eu fiz, mas no código do professor, foram adicionadas três propriedades extras pra organizar melhor os elementos na tela:

* **`padding: 15px;`**: Isso cria um "respiro" por dentro do card. Assim, o texto e o conteúdo não ficam espremidos e colados nas bordas da caixinha.
* **`margin: 10px;`**: Isso cria um espaço do lado de fora do card. Serve pra "empurrar" os outros cards pro lado e impedir que eles fiquem todos grudados parecendo um blocão só.
* **`display: inline-block;`**: Essa propriedade muda o comportamento do elemento. Ela faz com que os cards fiquem alinhados um do lado do outro (em linha), em vez de quebrar a linha e ficar um embaixo do outro, mas ainda respeitando o tamanho que a gente definiu.

## 2. O botão com `button:hover`
A instrução era só mudar a cor de fundo e o cursor do mouse na hora do hover. 

* No código do professor, rolou um extra: **`color: white;`**. Isso muda a cor da fonte para branco quando o mouse passa por cima do botão. Faz total sentido pra facilitar a leitura, já que o fundo muda pra um verde forte.

---

## Resumo da ópera
Meu código resolve 100% da lógica de seleção CSS que o desafio pedia. As coisas que ficaram diferentes foram só os "toques estéticos" de layout e espaçamento que o professor adicionou no CSS dele pra página ficar mais apresentável! 🚀