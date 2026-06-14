# Como aplicar no repositório tiagow2/tiagow2

## 1. Substituir o README

Copie o arquivo `README.md` para a raiz do repositório:

```bash
git clone https://github.com/tiagow2/tiagow2.git
cd tiagow2
# substitua o README.md pelo novo arquivo
git add README.md
git commit -m "docs: atualiza README do perfil"
git push
```

## 2. Adicionar a snake dos commits

Crie a pasta e arquivo:

```text
.github/workflows/generate-snake.yml
```

Depois copie o conteúdo do arquivo `generate-snake.yml` que veio neste pacote.

## 3. Ativar permissão da Actions

No GitHub, entre no repositório `tiagow2/tiagow2`:

1. Settings
2. Actions
3. General
4. Workflow permissions
5. Marque **Read and write permissions**
6. Salve

## 4. Rodar a primeira vez

1. Vá na aba **Actions**
2. Selecione **Generate Snake**
3. Clique em **Run workflow**

Depois que rodar com sucesso, a imagem da snake será publicada na branch `output` e aparecerá no README.

## Observação

Se a snake não aparecer imediatamente, aguarde alguns minutos e atualize a página. O GitHub às vezes demora para atualizar SVGs externos no README.
