# GM SAP Interview Masterclass

Sistema pessoal e interativo de preparação para entrevistas da posição **Senior Software Engineer — SAP Developer** na General Motors.

O projeto reúne perguntas técnicas, comportamentais e específicas sobre a GM em uma experiência de estudo prática, com respostas-modelo em inglês, simulação de entrevista e acompanhamento de progresso.

## Acessar o site

**[Abrir o GM SAP Interview Masterclass](https://juliobrenner.github.io/gm/)**

## Principais recursos

- 43 perguntas organizadas por tema;
- respostas-modelo e orientações para cada pergunta;
- cenários técnicos de SAP S/4HANA, ABAP, BTP, Fiori, OData e integrações;
- histórias comportamentais no formato STAR;
- perguntas específicas sobre GM e indústria automotiva;
- modo de simulação de entrevista com cronômetro;
- leitura em voz alta de perguntas e respostas pelo navegador;
- busca e filtros por categoria;
- acompanhamento de progresso salvo no navegador;
- temas claro e escuro;
- opção para imprimir ou salvar o material em PDF;
- layout responsivo para computador, tablet e celular.

## Como usar

1. Escolha uma categoria ou pesquise um assunto.
2. Leia ou escute a pergunta.
3. Responda em voz alta sem consultar o conteúdo.
4. Abra a resposta-modelo e compare os pontos principais.
5. Refaça a resposta usando suas próprias palavras e experiências reais.
6. Marque a pergunta como concluída quando conseguir responder naturalmente.

O modo **Mock Interview** seleciona perguntas para uma prática mais próxima de uma entrevista real.

## Categorias

- Screening & Introduction
- S/4HANA & ABAP
- Architecture & Clean Core
- SAP BTP & Cloud
- Fiori, UI5 & OData
- Integration & APIs
- Leadership & Delivery
- Behavioral STAR Stories
- GM & Automotive
- Questions for GM

## Executar localmente

O projeto é uma aplicação estática, sem dependências ou etapa de compilação. Basta baixar o repositório e abrir o arquivo `index.html` em um navegador moderno.

Também é possível iniciar um servidor HTTP local na pasta do projeto:

```bash
python3 -m http.server 8000
```

Depois, acesse `http://localhost:8000`.

## Publicação

O site é publicado automaticamente no GitHub Pages a partir da branch `main`, usando o workflow localizado em `.github/workflows/pages.yml`.

## Estrutura do projeto

```text
.
├── .github/workflows/pages.yml  # Publicação no GitHub Pages
├── .nojekyll                    # Desativa o processamento pelo Jekyll
├── index.html                   # Aplicação completa: conteúdo, estilos e scripts
└── README.md                    # Documentação do projeto
```

## Observação importante

Este material é um apoio para estudo. As respostas devem ser ajustadas à experiência profissional real do candidato. Informações recentes sobre a GM, a vaga e o mercado automotivo devem ser verificadas novamente antes da entrevista.

## Uso

Projeto pessoal de preparação para entrevistas.
