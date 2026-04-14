# Relatório - Coelinhos da Páscoa

> [!CAUTION]
> - Lembre-se que você <ins>**não pode utilizar ferramentas de IA para
>   escrever este relatório**</ins>

## Dados do aluno

- **Cartão UFRGS**: <mark>`324541`</mark>
- **Nome**: <mark>`Vinícius Gross Castro`</mark>

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

> [!IMPORTANT]
> - Coloque aqui todas as informações necessárias para que alguém
>   (pessoa ou ferramenta de IA) possa reproduzir os seus passos para
>   solucionar o problema
> - Escreva em formato imperativo, como se fosse um *prompt* com as
>   instruções a serem seguidas na solução do problema
> - Seja objetivo e conciso: quanto *menos palavras* você utilizar,
>   melhor
> - Seja técnico e use terminologia adequada: assuma que quem irá ler
>   os seus passos possui conhecimento de Ciência da Computação e
>   Computação Gráfica
> - Caso você queira incluir informações "longas" (como algum *prompt*
>   grande usado com alguma ferramenta de IA), crie arquivos à parte e
>   adicione links no texto (por exemplo, crie o arquivo `PROMPTS.md`
>   e adicione um link markdown `[os prompts detalhados estão
>   aqui](PROMPTS.md)`)
> - Novamente, lembre-se que você *não pode utilizar ferramentas
>   de IA para escrever este relatório*

1. Entender o que cada parte do main.cpp faz, e quais arquivos são mais relevantes para a realização do trabalho
2. Testar Matrix_Translate, Matrix_Scale e Matrix_Rotate_* para entender o efeito de cada função no objeto
3. Ajustar posição dos objetos e da câmera com múltiplos testes
4. Verificar que as rotações utilizam radianos (e não graus como suspeitava inicialmente)
5. Experimentar diferentes ordens de multiplicações de matrizes para entender como afeta o resultado
6. Implementar animação usando a função glfwGetTime()
7. Construir movimento do coelho com rotação e translação (bunny_movement)
8. Implementar órbita dos ovos usando rotação + translação + rotação inversa
9. Ajustar eixo de rotação até obter a órbita mais próxima do exemplo
10. Criar múltiplos objetos usando múltiplas chamadas de DrawVirtualObject
11. Substituir repetição por um for para gerar vários coelhos
12. Usar variação de tempo com "angle + i" para evitar movimentos iguais
13. Usar if (i % 4 == 0) para adicionar rotação própria em alguns coelhos
14. Refinar parâmetros (velocidade, posição, raio) para ficar mais próximo do pedido, por tentativa e erro

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

A maior dificuldade foi entender a ordem de multiplicação das matrizes e como afeta o resultado, já que não pareceu muito intuitivo a princípio. Isso causou vários resultados inesperados e até mesmo engraçados.

Também houve confusão entre rotação de órbita, rotação do próprio objeto e da escolha correta dos eixos.

No geral, o entendimento veio principalmente através de testes e ajustes incrementais.

## Você acha que conseguiu resolver o problema de forma adequada?

Sim. O código pode não estar em perfeito estado ou o mais otimizado possível, mas acredito que o resultado está muito próximo do esperado.

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

<mark>Essa atividade ajudou muito a entender como transformações e animações em OpenGL funcionam, principalmente por causa da parte visual. Testar pequenas mudanças no código e ir corrigindo aos poucos foi essencial para alcançar isso.</mark>

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

<mark>`<preencher>`</mark>
