# PetVida — Clínica Veterinária & Estética Animal

Projeto acadêmico desenvolvido para a disciplina **Design Profissional — Produção de Portfólio & Desenvolvimento Empresarial**.

## 1. Briefing do problema

A Clínica PetVida realiza consultas, vacinação, cirurgias de pequeno porte, banho e tosa. Atualmente, o controle dos agendamentos é feito em uma agenda de papel na recepção.

Com o crescimento do atendimento, esse processo passou a gerar conflitos de horários, esquecimentos de consultas e banhos, horários ociosos e dificuldade para localizar históricos médicos em arquivos físicos.

## 2. Solução proposta

A solução escolhida foi um **site/web app responsivo**, por ser uma alternativa simples e acessível para centralizar as principais informações da clínica.

O protótipo apresenta:

- Agendamento digital;
- Cadastro visual de serviços;
- Consulta do histórico do pet;
- Visualização de próximos atendimentos;
- Estrutura preparada para futuros lembretes automáticos;
- Integração conceitual entre serviços de estética e informações de saúde.

### Justificativa da decisão de design

Um web app foi escolhido porque pode ser acessado pelo navegador em computador ou celular, sem exigir a instalação de um aplicativo. A proposta também permite que a clínica evolua o protótipo para um sistema completo posteriormente.

## 3. Protótipo / telas

O projeto contém as seguintes áreas:

1. **Início** — apresentação da PetVida e acesso rápido ao agendamento.
2. **Serviços** — consultas, vacinação, banho e tosa e histórico.
3. **Agendamento** — formulário para tutor, pet, serviço, data e horário.
4. **Histórico do pet** — dados básicos e linha do tempo de atendimentos.
5. **Contato** — informações institucionais da clínica.

## 4. Arquitetura

O projeto utiliza uma estrutura web simples:

```text
petvida-clinica/
├── index.html
├── style.css
├── README.md
├── LICENSE
├── .gitignore
└── assets/
```

### Tecnologias

- HTML5
- CSS3
- JavaScript básico para a confirmação visual do protótipo
- Git e GitHub

Não são utilizadas APIs externas, bancos de dados ou credenciais.

## 5. Como executar

### Opção 1 — navegador

Baixe ou clone o repositório e abra o arquivo `index.html` no navegador.

### Opção 2 — VS Code

1. Abra a pasta do projeto no VS Code.
2. Abra `index.html`.
3. Execute com a extensão Live Server, se disponível.

## 6. Publicação no GitHub

Crie um repositório chamado:

`petvida-clinica`

Depois envie os arquivos do projeto para o repositório.

O repositório deve ficar público para facilitar a avaliação da atividade.

## 7. Segurança

O projeto não possui senhas, tokens, chaves de API ou outras credenciais. O `.gitignore` também impede o envio de arquivos comuns do sistema e dependências.

## 8. Objetivo do projeto

O objetivo é demonstrar como uma solução digital pode responder à dor apresentada pela PetVida, substituindo parte do processo manual por uma experiência organizada de agendamento e consulta das informações dos pets.

## 9. Observação acadêmica

Este projeto é um **protótipo acadêmico**. Os dados exibidos na interface são fictícios e servem somente para demonstrar a solução proposta.
