# Aviso

Conteúdo produzido durante um curso aberto. O material original não pertence a mim.

---

Os tipos enumerados da linguagem são interessantes. Não são constantes no sentido estrito: ficam no meio do caminho entre constante e classe. As diferenças que valem registrar:

- São declarados no começo do arquivo com a palavra reservada própria, não com a de classe;
- Nos exemplos que vi, o construtor é privado;
- Aceitam métodos, inclusive os de acesso às propriedades, como qualquer classe;
- Podem carregar mais de uma propriedade, ou seja, não são só uma lista de textos. Veja o exemplo abaixo;
- Os valores são declarados dentro do próprio tipo, chamando o construtor privado;
- Cada tipo enumerado vive no seu próprio arquivo de código;
- Depois de declarados, é possível encadear chamadas nos valores, por exemplo consultando a propriedade de um deles.

Um detalhe prático: como o construtor é privado, o conjunto de instâncias fica fechado — não dá para criar valores novos em tempo de execução, o que é justamente o que se espera de uma enumeração.