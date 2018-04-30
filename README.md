# Biblioteca-ButterKnife

![alt text](https://i.imgur.com/6k9efZT.png)

Neste artigo irei explicar o funcionamento da biblioteca ButterKnife, e por que usa-lá para isso irei responder três perguntas:
1- Como essa biblioteca pode ser utilizada?
2- quais as vantagens de usá-la?
3- há bibliotecas semelhantes a elas? Liste.

1- quais as vantagens de usá-la?
Ela reduz drasticamente o código quando precisamos acessar elementos dos nossos layouts xml, e torna ainda mais fácil o uso de listeners e podemos sempre usar a biblioteca quando utilizamos as views para referência-lás, ela funciona através do uso de annotations, assim reduz o código repetido.
 
2- Como essa biblioteca pode ser utilizada?
A biblioteca  Butter Knife foi criada por JakeWharton que atualmente está na versão 8.1.1, e para ser utilizada basta  ir no Android Studio e ir em : File > Project Structure”>“app” e depois na aba “Dependencies” e depois > soma verde > Library Dependencie”. Então escreva “butterknife”, e adicionar a biblioteca.

3- Exista bibliotecas semelhantes a elas? Liste.
http://jakewharton.github.io/butterknife/#click-injection
http://jakewharton.github.io/butterknife/#multi-method-listeners
http://jakewharton.github.io/butterknife/javadoc/



Podemos notar aqui a declaração e o uso do fundViewById, isso é totalmente eliminado com o usa da ButterKnife, imagine isso em uma tela com muitos componentes visuais, ele acelera enormemente o desenvolvimento.

Mais informações em: https://lucasfogacadev.000webhostapp.com/2018/04/utilizando-a-biblioteca-butterknife

