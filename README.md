# Introdução
O projeto da disciplina envolve duas atividades diferentes relacionadas à Matemática Computacional.

Na primeira fase, você deverá aplicar os conceitos trabalhados em Lógica Proposicional para explorar circuitos de portas lógicas. Na segunda fase você deverá desenvolver uma proposta relacionada à área de Álgebra Linear, utilizando sistemas de equações lineares.

# Enunciado da fase 01
(**)Uma aplicação da Lógica Proposicional: PORTAS LÓGICAS(**)

O matemático americano Claude Shannon identificou, em 1938, uma forte correlação entre a Lógica Proposicional e a lógica de circuitos e foi o primeiro a sugerir que a Álgebra Booleana poderia unificar as duas abordagens, servindo como formalismo para modelar circuitos lógicos ou redes lógicas. Uma importante consequência desse trabalho é que os circuitos lógicos podem ser modelados, analisados, testados e otimizados independentemente de sua implementação.

Praticamente todos os circuitos de um computador digital são modelados em termos de uma álgebra booleana cujo conjunto suporte possui dois elementos: verdadeiro e falso. É claro que o projeto de computadores digitais deve considerar diversos outros fatores, como o tempo de propagação de um sinal, minimização de problemas decorrentes de falhas de alguns componentes etc. 

Consideremos somente os aspectos referentes à Álgebra Booleana, uma aplicação da Lógica Proposicional, concentrando em dois tipos de portas e um inversor, a saber:
• porta E, correspondendo à conjunção, usualmente denotada pelo símbolo “ • ”;
• porta OU, correspondendo à disjunção, usualmente denotada pelo símbolo “ + ”; 
• inversor, eventualmente denominado porta NÃO, correspondendo à negação, usualmente denotado pelo símbolo “ ʹ ”. 

![image](https://github.com/user-attachments/assets/834581ee-1ddb-4e62-853b-19ee56907bd1)

Expressões diferentes (e com diferentes diagramas de circuitos) podem ser equivalentes, ou seja, podem implementar a mesma função lógica. Assim, outro ponto de fundamental importância na construção de circuitos são as técnicas de minimização de expressões lógicas, através da aplicação das propriedades.

Retirado de:  MENEZES, Paulo Blauth.  Matemática discreta: para computação e informática. 4. ed. Porto Alegre: Bookman, 2013.

Com base no texto “Uma aplicação da Lógica Proposicional: PORTAS LÓGICAS” de Menezes (2013), propomos que você assista o vídeo do professor Marcelo Cohen, disponível em https://www.youtube.com/watch?v=1603LGQo5c8 sobre tal aplicação da Lógica Proposicional, aprofundando seus conhecimentos e, posteriormente, realize o seguinte trabalho:

• Monte um circuito que possua quatro entradas (escolha usar  p,q,r,s,  ou  A,B,C,D) e uma saída f (p,q,r,s) ou f (A,B,C,D), conforme for o caso. Neste circuito inicial, todos os operadores (and, or, not) precisam aparecer, pelo menos, uma vez.
• Apresente a expressão lógica equivalente à função f.
• Utilizando as propriedades da Lógica Proposicional, reduza ao máximo a expressão lógica apresentada inicialmente, indicando a cada linha qual a propriedade que foi aplicada.
• Represente o circuito em sua forma simplificada, ou seja, utilizando menos proposições e operadores lógicos que na expressão e no circuito original.  

# Enunciado da fase 02
(1)  Acesse o livro Álgebra Linear com Aplicações, de Howard Anton e Chris Rorres, 10ª edição, disponível em:
https://primo-pmtna01.hosted.exlibrisgroup.com/permalink/f/1fm4a6p/sfx26800000000046862

Ao acessar esse endereço em seu navegador, clique na opção “acesso online”, depois clique em “OK” e, por fim, clique em “Acessar com Conta Office”;

(2) Faça a leitura das seguintes seções para aprofundar seus conhecimentos sobre sistemas lineares e ter acesso a exemplos de aplicações, conforme é solicitado no projeto: 
Seção 1.8: Aplicação de sistemas lineares - páginas 73 à 80
Seção 10.3: As mais antigas aplicações da álgebra linear – páginas 536 à 541;  
 
(3) Após a leitura, pesquise livremente outras aplicações para sistemas lineares, a fim de identificar diversas situações problemas do cotidiano que podem ser solucionadas por meio de sistemas lineares;  

(4) Em seguida, desenvolva um documento para apresentar uma situação-problema contextualizada que envolva a aplicação da álgebra linear, utilizando sistemas de equações lineares. Para caracterizar essa situação problema, leve em consideração que seu documento deve atender aos seguintes aspectos:

• Escreva ao menos um parágrafo descrevendo uma situação do mundo real para a qual pode haver a aplicação de sistemas de equações lineares. Situações como essa poderiam ser a criação de uma empresa, análise de redes e circuitos, entre outras. Descreva e contextualize a situação escolhida;
• A situação escolhida por você deve envolver, no mínimo, quatro incógnitas que se relacionem;
• Você deve aplicar um método de resolução de sistemas lineares;
• Descreva todos os passos da resolução;
• Analise o resultado obtido.

Para resolver o sistema em questão, você pode utilizar o software Octave (https://octave.org/), apresentado nas aulas 8, 9 e 10. Caso o utilize, você pode copiar as telas como imagem para inserir no seu documento de texto (template).
