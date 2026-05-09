# Projeto: Redução de Carga Cognitiva via Manipulação Direta 

## O que eu fiz?
Para esse trabalho, decidi mexer em uma parte que sempre achei estranho em sistemas de trabalho: a área de dar permissões para novos funcionários. Geralmente, isso é uma lista enorme de nomes estranhos e códigos que ninguém entende, e você tem que ficar marcando caixinhas (checkboxes) torcendo para não errar.

## Qual era o problema?
O sistema antigo forçava o usuário a **lembrar** o que cada sigla significava. Isso gera um cansaço mental enorme (a tal da carga cognitiva), porque se você esquece o que o botão "ADM_LOG_V1" faz, você tem que parar tudo e procurar um manual. É o que chamamos de estilo "punitivo".

## Minha Solução (O "Pulo do Gato")
Eu refiz essa lógica usando **Manipulação Direta**. 
Em vez de ler códigos e marcar caixas, agora o administrador só precisa **olhar o ícone, reconhecer a função e arrastar** para o lado do usuário.

- **Antes:** O usuário tinha que saber de cor ou pesquisar siglas (Esforço de Lembrança).
- **Depois:** O usuário bate o olho no ícone de "Backup" ou "Usuários" e já sabe o que é (Reconhecimento Visual).

Isso encurta o caminho entre o que a pessoa quer fazer e a ação real na tela. É muito mais rápido e difícil de errar.

## Como testar
1. Baixe o arquivo `index.html`.
2. Abra no navegador.
3. É só clicar e arrastar as permissões da esquerda para a direita.

## Tecnologias
Usei o básico que funciona: HTML, CSS para deixar o visual limpo e um pouco de JavaScript para fazer o "arrasta e solta" (Drag and Drop) funcionar de verdade.
