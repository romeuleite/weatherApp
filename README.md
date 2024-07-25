# WeatherApp

## Descrição

O **WeatherApp** é um aplicativo Android desenvolvido em Kotlin que exibe informações climáticas usando a API Open Weather. O app foi construído seguindo as práticas modernas de desenvolvimento de aplicativos Android, utilizando uma arquitetura reativa e em camadas, fluxo de dados unidirecional (UDF) e várias outras técnicas avançadas para garantir um código limpo, eficiente e fácil de manter.

![Imagem do WhatsApp de 2024-07-25 à(s) 15 36 53_594175a9](https://github.com/user-attachments/assets/49fbc41c-83ae-4ac7-9f8c-2f1bf16ffebf)

## Funcionalidades

- Exibição de informações climáticas atuais.
- Interface de usuário responsiva e moderna.
- Gerenciamento eficiente de estados da interface.
- Integração com a API Open Weather para obter dados climáticos em tempo real.

## Tecnologias Utilizadas

- **Kotlin**: Linguagem principal utilizada no desenvolvimento do aplicativo.
- **Ktor**: Framework utilizado para realizar requisições HTTP.
- **Hilt**: Biblioteca para injeção de dependência.
- **Open Weather API**: Serviço utilizado para obter informações climáticas.
- **Corrotinas e Fluxos**: Para operações assíncronas e reativas.
- **Android Studio**: Ambiente de desenvolvimento integrado (IDE) utilizado.

## Arquitetura

O WeatherApp foi desenvolvido utilizando uma arquitetura moderna conforme descrito no [guia de arquitetura do Android](https://developer.android.com/topic/architecture?hl=pt-br). Abaixo estão alguns dos princípios e práticas seguidos:

- **Arquitetura Reativa e em Camadas**: O app segue uma arquitetura em camadas (Camada de Dados, Camada de Domínio e Camada de Apresentação) promovendo a separação de responsabilidades.
- **Fluxo de Dados Unidirecional (UDF)**: Garantindo um fluxo de dados previsível e fácil de seguir em todas as camadas do app.
- **Camada de Interface com Detentores de Estado**: Gerenciando a complexidade da interface de usuário de forma eficiente e escalável.
- **Práticas Recomendadas para Injeção de Dependência**: Utilizando Hilt para gerenciar dependências de maneira eficiente e segura.

## Contribuição
Esse app foi inspirado a partir do video do canal [Douglas Motta](https://youtu.be/yYB8evI5wj0?si=KtP0scAnFywPG54t)

