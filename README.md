# Realidade Aumentada — Manual Interativo do Torno CNC

> Atividade acadêmica de Realidade Aumentada desenvolvida para a Faculdade de Tecnologia e Escola SENAI Antonio Adolpho Lobbe.

## Demonstração

Acesse a aplicação através do GitHub Pages:

**[🚀 Acessar o Manual Interativo de RA](https://marcosvxn.github.io/Aula-RA_ManualCNC/)**

> Para utilizar a experiência, acesse pelo celular e permita o acesso à câmera.

## Sobre o projeto

Este projeto consiste no desenvolvimento de uma aplicação de **Realidade Aumentada (RA)** voltada à apresentação de informações sobre um torno CNC.

A aplicação utiliza a câmera de um dispositivo para reconhecer uma imagem de referência e, a partir desse reconhecimento, disponibilizar pontos interativos sobre diferentes componentes do torno.

Ao selecionar um dos pontos apresentados na tela, o usuário pode visualizar informações relacionadas ao componente selecionado, proporcionando uma experiência interativa de apoio ao aprendizado.

## Objetivo

O objetivo da atividade é aplicar conceitos de desenvolvimento web e Realidade Aumentada na criação de uma experiência interativa relacionada ao ambiente industrial.

Por meio da aplicação, busca-se demonstrar como tecnologias de RA podem ser utilizadas para apresentar informações de maneira visual e interativa, facilitando a compreensão dos componentes de um torno CNC.

## Funcionalidades

- Reconhecimento de imagem através da câmera do dispositivo;
- Rastreamento do objeto em Realidade Aumentada;
- Exibição de pontos interativos sobre o torno CNC;
- Visualização de informações sobre os componentes;
- Atualização dos pontos conforme a posição do objeto é alterada;
- Interface adaptada para utilização em dispositivos móveis;
- Indicação do estado atual da experiência de Realidade Aumentada.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- A-Frame
- MindAR
- Three.js

## Componentes apresentados

A aplicação apresenta informações relacionadas a diferentes partes do torno CNC, incluindo:

- Cabeçote e placa;
- Torre de ferramentas;
- Painel de comando CNC;
- Proteção e segurança.

## Funcionamento

O funcionamento da aplicação pode ser representado pelo seguinte fluxo:

```text
Câmera do dispositivo
        ↓
Reconhecimento da imagem
        ↓
Identificação do target
        ↓
Ativação da experiência de RA
        ↓
Exibição dos pontos interativos
        ↓
Interação do usuário
        ↓
Exibição das informações
```

Os pontos interativos são posicionados de acordo com coordenadas relacionadas ao target reconhecido. Dessa forma, eles acompanham visualmente o objeto durante a experiência de Realidade Aumentada.

## Estrutura do projeto

```text
Aula-RA_ManualCNC/
│
├── assets/
│   └── targets/
│       └── torno-cnc.mind
│
├── css/
│   └── style.css
│
├── js/
│   └── app.js
│
├── index.html
└── README.md
```

## Execução

Para executar o projeto, é necessário utilizar um ambiente que permita o acesso à câmera do dispositivo.

O projeto está disponível através do **GitHub Pages**.

Após acessar a aplicação:

1. Permita o acesso à câmera;
2. Aponte a câmera para a imagem utilizada como referência;
3. Aguarde o reconhecimento do target;
4. Interaja com os pontos apresentados;
5. Selecione um ponto para visualizar as informações correspondentes.

## Aplicação acadêmica

Este projeto foi desenvolvido como parte de uma atividade acadêmica de **Realidade Aumentada**, buscando relacionar conceitos de programação, desenvolvimento web e tecnologias imersivas.

A atividade também permite explorar conceitos relacionados à interação entre elementos HTML e objetos posicionados em um ambiente tridimensional.

## Objetivos de aprendizagem

Com o desenvolvimento da atividade, foram trabalhados conceitos como:

- Desenvolvimento de aplicações web;
- Manipulação do DOM;
- Eventos em JavaScript;
- Estruturação de interfaces com HTML e CSS;
- Realidade Aumentada baseada em reconhecimento de imagem;
- Rastreamento de objetos;
- Coordenadas em ambientes 3D;
- Integração entre bibliotecas e aplicações web;
- Interação em dispositivos móveis.

## Observação

Este projeto possui finalidade **exclusivamente acadêmica e educacional**.

As informações apresentadas sobre o torno CNC têm caráter didático e não substituem treinamentos técnicos, procedimentos de segurança ou documentação fornecida pelo fabricante da máquina.

## Instituição

**Faculdade de Tecnologia e Escola SENAI Antonio Adolpho Lobbe**

### Atividade

**Realidade Aumentada — Manual Interativo do Torno CNC**

## Autor

**MarcosVxn**

---

Projeto acadêmico desenvolvido para fins educacionais.
