# Landing Page MonitoraSEI

Landing page estática, responsiva e pronta para publicação no GitHub Pages.

## Arquivos

- `index.html`
- `styles.css`
- `script.js`

## Antes de publicar

Abra o arquivo `index.html` e substitua:

```text
SEU-EMAIL-AQUI
```

pelo e-mail que receberá as mensagens do formulário.

O formulário utiliza o serviço FormSubmit. No primeiro envio, o serviço poderá solicitar uma confirmação por e-mail.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie estes arquivos para a raiz do repositório.
3. Abra `Settings`.
4. Entre em `Pages`.
5. Em `Build and deployment`, selecione `Deploy from a branch`.
6. Escolha a branch `main` e a pasta `/root`.
7. Salve.

Após alguns minutos, a página ficará disponível em:

```text
https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/
```

## Domínio próprio

No GitHub Pages, você também pode configurar um domínio ou subdomínio próprio pela opção `Custom domain`.

## Personalização rápida

No arquivo `styles.css`, as principais cores estão no início:

```css
:root {
  --primary: #0f766e;
  --dark: #0f172a;
}
```

No `index.html`, ajuste textos, metas do piloto e contatos conforme sua apresentação.
