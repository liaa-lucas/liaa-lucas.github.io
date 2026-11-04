# liaa-lucas.github.io · Projeto Farol

Site do Projeto Farol para a disciplina Laboratório de IA Aplicada (PPGES/Unipampa).
Página única (`index.html`), sem dependências além da fonte Nunito.

## Publicar no GitHub Pages

O GitHub só serve `<nome>.github.io` na raiz quando o repositório tem **exatamente o nome da conta**.

1. Crie uma conta (ou organização) no GitHub chamada `liaa-lucas`.
2. Nela, crie um repositório público chamado `liaa-lucas.github.io`.
3. Envie os arquivos:
   ```
   cd liaa-lucas.github.io
   git init
   git add .
   git commit -m "Site do Projeto Farol"
   git branch -M main
   git remote add origin https://github.com/liaa-lucas/liaa-lucas.github.io.git
   git push -u origin main
   ```
4. Em Settings › Pages, confira: Source = "Deploy from a branch", Branch = `main` / `(root)`.
5. Em 1 ou 2 minutos o site abre em https://liaa-lucas.github.io

## Atualizar toda semana

Abra `index.html` e procure **DIÁRIO DE BORDO** (no fim do arquivo):

1. Acrescente um item no fim da lista `DIARIO` (data, versão, título, itens e, se quiser, a lição).
2. Tire `atual: true` do item anterior e coloque no novo (é o marco amarelo).
3. Em `ANDAMENTO`, ajuste `atualizado`, `status` e `gabaritoHoras` (a barra de progresso se ajusta sozinha).
4. `git add . && git commit -m "Semana X" && git push`.
