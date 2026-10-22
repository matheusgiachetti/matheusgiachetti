# Como publicar o README de perfil

## 1. Crie o repositório especial do perfil

No GitHub, crie um repositório **público** com o nome exato:

```text
matheusgiachetti
```

Ele deve pertencer à conta `matheusgiachetti`, ficando no endereço `https://github.com/matheusgiachetti/matheusgiachetti`. Esse é o formato que faz o GitHub exibir o arquivo `README.md` na página do perfil.

Copie o arquivo `README.md` deste pacote para a raiz desse repositório.

## 2. Ative a animação Snake

1. No mesmo repositório, crie a pasta `.github/workflows/`.
2. Copie `generate-snake.yml` para `.github/workflows/generate-snake.yml`.
3. No GitHub, acesse **Settings → Actions → General → Workflow permissions** e escolha **Read and write permissions**. Salve a alteração.
4. Abra a aba **Actions**, selecione **Gerar animação Snake** e clique em **Run workflow** uma vez.

O workflow gera dois SVGs e os publica no branch `output`. Depois da primeira execução bem-sucedida, a animação aparecerá no README e será atualizada diariamente.

## 3. Cartões de estatísticas

O README usa o serviço público [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) para mostrar estatísticas e linguagens da conta. Não exige token para o uso básico, mas depende de um serviço externo e pode sofrer limites temporários. Se algum cartão não carregar, aguarde e atualize a página; se preferir não depender desse serviço, remova as duas linhas `<img>` da seção **Estatísticas**.

## 4. Projetos em destaque

O texto evita citar projetos não confirmados. Para exibir projetos reais no perfil, abra cada repositório que quiser destacar e use **Pin** na aba de repositórios do seu perfil do GitHub. Atualize também a lista da seção **Projetos em destaque** quando houver projetos que você queira nomear publicamente.

## 5. Links sociais

- LinkedIn: `https://www.linkedin.com/in/matheus-giachetti-614685346/`
- Instagram: `https://instagram.com/gct_jequiti`

Os badges usam cores inspiradas na paleta Bootstrap e podem ser ajustados diretamente nos parâmetros de cada URL do `shields.io`.
