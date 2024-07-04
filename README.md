![image](https://github.com/ViihSN/cronometro/assets/93055828/b0ca7d63-f30b-4b63-973b-631239724de7)

# Cronômetro React

Este projeto é um cronômetro simples desenvolvido em React. Ele possui um botão para iniciar/pausar o cronômetro e outro botão para resetar o cronômetro.

## Estrutura do Projeto

- `App.js`: Componente principal que contém a lógica do cronômetro.
- `style.css`: Arquivo de estilos para o componente.
- `assets/cronometro.png`: Imagem usada no cronômetro.

## Instalação

Para rodar este projeto localmente, siga os seguintes passos:

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   
2. Navegue até a pasta do projeto:
   ```bash
   cd seu-repositorio

3. Instale as dependências:
   ```bash
   npm install
4. Inicie o servidor de desenvolvimento:
   ```bash
   npm install

## Componente `App`
O componente App é um componente de classe que contém a lógica do cronômetro.

## Estado Inicial
`numero`: Mantém o valor atual do cronômetro.
`botao`: Texto do botão que alterna entre "VAI" e "PAUSAR".

## Métodos
`vai()`: Inicia ou pausa o cronômetro. Quando iniciado, o cronômetro incrementa o valor de numero em 0.1 a cada 100 milissegundos. Quando pausado, a contagem é interrompida.
`limpar()`: Reseta o cronômetro para zero e redefine o texto do botão para "VAI".

## Renderização
O componente renderiza:
- Uma imagem (cronometro.png).
- Um elemento <a> que exibe o valor atual do cronômetro.
- Dois botões: um para iniciar/pausar e outro para limpar o cronômetro.

## Estilos
- Crie um arquivo `style.css` na pasta `src`.
