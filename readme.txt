LinkFree — Instruções rápidas de uso
O LinkFree é uma página simples para compartilhar seus contatos, redes sociais e projetos.
Para personalizar, você só precisa editar um arquivo: config.js.
________________________________________
1. Abrir o projeto
1.	Baixe ou clone o projeto
2.	Abra a pasta no seu computador
3.	Dê duplo clique em index.html para abrir no navegador
Se algo não atualizar, pressione Ctrl + F5
________________________________________
2. Trocar a foto/logo
1.	Coloque sua imagem dentro da pasta assets/
2.	Abra o arquivo config.js
3.	Altere a linha:
avatarUrl: "assets/avatar.jpg",
(Use o nome real do seu arquivo)
________________________________________
3. Editar nome e título do cabeçalho
No config.js, altere:
bannerLine1: "Seu Nome",
bannerLine2: "Seu Título",
bannerLine3: “bio”,
Exemplo:
bannerLine1: "Prof: João",
bannerLine2: "Informática",
bannerLine3: “blablabla”
________________________________________
4. Editar a bio
No config.js, altere:
bio: "Escreva aqui uma breve descrição sobre você.",
________________________________________
5. Editar links e redes sociais
No config.js, vá até a parte:
sections: [
Cada link segue este modelo:
{
  title: "Nome do link",
  subtitle: "Descrição curta",
  url: "https://seulink.com",
  iconKey: "instagram"
}
Você pode:
•	editar links existentes
•	apagar links
•	adicionar novos
________________________________________
6. Editar o texto do rodapé
No config.js, altere:
footerText: "© 2026 Seu Nome"
________________________________________
7. Publicar no GitHub Pages
1.	Envie os arquivos para um repositório no GitHub
2.	Vá em Settings → Pages
3.	Selecione:
o	Branch: main
o	Folder: root /
4.	Clique em Save
5.	Aguarde o link ser gerado

