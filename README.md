# Conversor_Moedas
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/willianfrancisco/Conversor_Moedas/blob/main/LICENSE)

Converso de moedas de acordo com a cotação do dollar ou euro no dia.

# Sobre o Projeto

O conversor de moedas e um aplicativo mobile desenvolvido em flutter.
O app consiste em um converor de tres tipos de moeda o Real, Dollar e Euro, o intuito e facilitar a consulta de preços de produtos importados sem precisar pesquisar o valor de compra da Moeda no dia em que for realizar a compra,utilizando os dados do hgbrasil.com ele consome a API  https://api.hgbrasil.com/finance e calcula o valor do produto conforme o valor da Moeda no respequitivo dia.

## Layout
![Mobile 1](https://github.com/willianfrancisco/Conversor_Moedas/blob/main/TelaInicial.PNG) ![Mobile 2](https://github.com/willianfrancisco/Conversor_Moedas/blob/main/Conversao.PNG)

## Tecnologia Ultilizada
- Flutter 
- Dart
- Visual Studio Code
- Android Studio

## Bibliotecas Ultilizadas
- package:http/http.dart
- dart:async
- dart:convert

## Como Executar o projeto

```bash
# clonar o repositorio
https://github.com/willianfrancisco/Conversor_Moedas.git

# usar o visual studio code ou android studio e abrir a pasta do projeto.
```

### Pré Requisitos
- Ter um Emulador Android Instalado.
- Ter o fluter Instalado e Configurado.
- Ter um editor como Android Studio ou Visual Studio Code(Com extensão do Fluter Instalado).

### Importante
- A versão mais recente do Flutter não vem com a biblioteca do pacote Http incluído por padrão.
- Para incluir Devemos adicionar o plugin do Http no arquivo pubspec.yaml.
  - cupertino_icons: ^0.1.2
  - http: ^0.12.0+2  
- Tome bastante cuidado com o alinhamento! O http deve ficar no mesmo alinhamento do cupertino_icons e logo abaixo do mesmo!
- Logo após clique no botão flutter packages get, caso não apareça a opção o seu flutter já possui o pacote Http instalado.

## Autor
Willian Francisco de Souza

https://www.linkedin.com/in/willian-francisco-b47605127/
