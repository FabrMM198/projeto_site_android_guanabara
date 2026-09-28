# Curiosidades de Tecnologia

## Objetivo

Projeto de estudo em HTML e CSS criado durante o curso do Curso em Vídeo. A página principal apresenta a história do mascote do Android, o Bugdroid, e curiosidades sobre os nomes das versões do sistema.

## Funcionalidades

- Exibe um artigo com títulos, parágrafos, imagens e links externos.
- Mostra imagens adaptadas a diferentes larguras de tela por meio do elemento `<picture>`.
- Incorpora um vídeo do YouTube sobre o Android.
- Apresenta uma lista em duas colunas com os nomes de versões antigas do Android.
- Organiza a aparência em arquivos CSS separados para estrutura geral, cabeçalho, conteúdo, imagens e rodapé.
- Inclui uma página separada para demonstrar responsividade.

## Arquivos e pastas

### Páginas

- `android.html`: página principal. Contém o cabeçalho, menu, artigo sobre a história do mascote, imagens, vídeo, lista de versões e rodapé. Ela carrega os estilos da pasta `style/` e os recursos da pasta `img/`.
- `responsivo.html`: página independente de teste de responsividade. Usa CSS interno e troca a imagem exibida conforme a largura da tela.
- `android-site.txt`: roteiro textual do conteúdo planejado para a página sobre o Android.

### Estilos

- `style/style.css`: define as variáveis de cores e fontes, aplica estilos globais e registra a fonte personalizada Android.
- `style/header.css`: estiliza o cabeçalho e os links do menu, incluindo o estado ao passar o cursor.
- `style/main.css`: estiliza o conteúdo principal, títulos, parágrafos, links, áreas do artigo, vídeo e lista de versões.
- `style/img.css`: controla o tamanho e o alinhamento das imagens do artigo.
- `style/footer.css`: define a aparência do rodapé.

### Recursos

- `img/`: imagens do mascote, ilustrações da história, versões menores para telas estreitas e favicon.
- `fontes/idroid.otf`: fonte personalizada usada nos títulos.

## Como visualizar

Abra `android.html` em um navegador para ver a página principal. Para visualizar o exemplo de responsividade, abra `responsivo.html`. Não é necessário instalar dependências nem executar um processo de build.