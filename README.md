# Portfólio pessoal

Site estático para apresentar seus projetos, experiência, currículo e formas de contato.

## Personalização rápida

1. Abra `index.html` para atualizar seus dados, caso necessário. Os links atuais são GitHub, LinkedIn e Instagram do Marcello.
2. Edite os textos dos projetos, experiência e seção sobre mim.
3. Preencha `curriculo.txt` com seus dados reais. Se preferir um PDF, substitua o arquivo e atualize o link do botão no `index.html`.
4. Em `styles-tech.css`, as cores principais ficam nas variáveis no começo do arquivo.

## Rodar localmente

Com Python instalado:

```bash
python -m http.server 8000
```

Acesse `http://localhost:8000`.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Abra o terminal nesta pasta e rode:

```bash
git init
git add .
git commit -m "cria portfolio pessoal"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
git push -u origin main
```

3. No GitHub, abra `Settings > Pages`.
4. Em **Build and deployment**, escolha `Deploy from a branch`, selecione `main` e a pasta `/ (root)`.
5. Salve. O endereço será parecido com `https://seu-usuario.github.io/seu-repositorio/`.
