# Monitoramento ASU Website

O objetivo deste projeto é armazenar em um só lugar o monitoramento de todos os programas do ASU - Avaliação de Satisfação do Usuário, atualmente contendo o ASU Mãe Coruja e o ASU CAPS. Na tela individual do programa é possível ver a lista de todos os formulários e através dessa tela ser redirecionado para seus respectivos monitoramentos. No momento todos os formulários de pesquisa e os monitoramentos são feitos através da ferramenta REDCap.

## Conteúdo

- [Versão do Mobirise](#versão-do-mobirise)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Imagens e Créditos](#imagens-e-créditos)
- [Alterações e Upgrades](#alterações-e-upgrades)

## Versão do Mobirise

Este projeto foi criado com o Mobirise Website Builder na versão 5.6.8.

## Estrutura do Projeto

O projeto consiste atualmente em três páginas:

1. **Tela Inicial**: Esta é a página inicial que lista os programas.
2. **Lista Mãe Coruja**: Esta página lista as unidades monitoradas do projeto e redireciona para as telas de monitoramento.
3. **Lista CAPS**: Similar à página do Mãe Coruja, esta página exibe a lista das unidades monitoradas do projeto e redireciona para as telas de monitoramento.


## Imagens e Créditos

- **Imagens**: As imagens utilizadas como background em cada tela do projeto são do Freepik.
- **Créditos de Imagem**: Apesar de serem grátis a licença necessita que sejam dados os devidos créditos aos autores.
- **Como dar créditos**: De acordo com que foi lido nas licenças, é só colocar um texto - mesmo que breve - falando que as imagens são do freepik e deixar uma tag <a> com o link para o site. Ex:. <a href="http://www.freepik.com">Designed by Freepik</a>

### Nota sobre os links do Freepik no Footer

Foi utilizado tanto os links individuais, que é fornecido na hora do download, quanto o link do site na documentação da licença e apesar de estar sem erros de sintaxe/digitação ainda assim o redirecionamento retorna uma tela com o erro 403 Forbidden. O link foi mantido conforme a documentação da licença, então não se preocupem.


## Alterações e Upgrades

- **Recomendações pós ajustes no HTML**: Para entregar o website nos padrões foram feitas algumas alterações diretamente no HTML, o comportamento padrão do Mobirise faz com que essas alterações não sejam refletidas no aplicativo mesmo após serem salvas. Então muito cuidado caso precise fazer alguma adição futuramente. A recomendação é salvar uma cópia do projeto do jeito que está no Github, além do clone que você vai utilizar para abrir no Mobirise. Ao abrir você vai perceber que tudo que foi feito pela IDE não ficará visível na tela do mobirise que ao salvar o projeto no aplicativo, esse projeto aberto irá sobrescrever tudo que não está nos padrão dele, ou seja, tudo que foi feito na IDE. É aí que entra a cópia reserva salva em outro diretório, é dela que você vai poder copiar os códigos que serão apagados no mobirise. 
- **Edições Adicionais**: Se houver necessidade de adicionar mais programas na tela inicial ou adicionar alguma tela que utilize dos mesmos recursos que já foram utilizados, recomendo apenas copiar, colar e editar diretamente na IDE sem precisar fazer o passo acima no aplicativo.
- **Mobirise e Bootstrap**: O Mobirise utiliza o Bootstrap, portanto, é possível aproveitar as classes do Bootstrap caso precise fazer alguma alteração além do aplicativo, mas lembre-se de importar as bibliotecas no cabeçalho do arquivo HTML. Caso não saiba como fazer, abra um arquivo .html que foi feito pelo mobirise e veja os caminhos.
- **Diretório de Assets**: Todas as imagens do projeto, o CSS e o JS dos componentes criados no Mobirise estão dentro da pasta "assets".
- **Links de Rodapé**: No final de cada arquivo .html criado com o Mobirise, há uma seção com a classe "display-7" contendo duas tags de parágrafo com links do Mobirise. Esses links NÃO DEVEM SER APAGADOS!!!.

