# Site de aplicativos — GitHub Pages

Site estático, responsivo e pronto para publicação gratuita no GitHub Pages.

## Antes de publicar

1. Abra `suporte/index.html`.
2. Substitua `SEUEMAIL@EXEMPLO.COM` pelo seu e-mail oficial.
3. Quando os aplicativos estiverem publicados, adicione os links da Google Play nas páginas dentro da pasta `apps`.
4. Revise a Política de Privacidade e os Termos de Uso para confirmar que correspondem exatamente às funções reais de cada aplicativo.

## app-ads.txt

O arquivo já está na raiz e contém:

```txt
google.com, pub-7909716286702325, DIRECT, f08c47fec0942fa0
```

Depois de publicar, ele deverá abrir em:

```text
https://SEUUSUARIO.github.io/app-ads.txt
```

## Forma recomendada de publicar

Para que o `app-ads.txt` fique na raiz do domínio:

1. Crie no GitHub um repositório chamado exatamente:
   `SEUUSUARIO.github.io`
2. Envie todo o conteúdo desta pasta para a raiz do repositório.
3. No GitHub, abra:
   `Settings > Pages`
4. Em “Build and deployment”, escolha:
   `Deploy from a branch`
5. Selecione a branch `main` e a pasta `/ (root)`.
6. Salve e aguarde a publicação.

O site ficará em:

```text
https://SEUUSUARIO.github.io/
```

## Configuração na Google Play Console

Use a URL principal do site como “Site do desenvolvedor”:

```text
https://SEUUSUARIO.github.io/
```

O domínio informado na loja precisa corresponder ao domínio onde o `app-ads.txt` está publicado.

## Estrutura

- `index.html` — página inicial
- `app-ads.txt` — declaração do AdMob
- `privacidade/` — política de privacidade
- `termos/` — termos de uso
- `suporte/` — suporte
- `apps/` — páginas individuais dos aplicativos
- `assets/` — estilos, JavaScript e favicon
- `.nojekyll` — evita processamento desnecessário do GitHub Pages

## Teste local

Abra `index.html` diretamente no navegador ou use uma extensão de servidor local, como “Live Server” no Visual Studio Code.
