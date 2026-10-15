# Site-alvo fictício para laboratório de phishing

Este repositório hospeda o **Portal Acadêmico — Fictícia S.A.**, um site estático
criado exclusivamente para uma atividade didática de Segurança de Sistemas.
A instituição, a identidade visual e os serviços apresentados são fictícios.
Este não é um portal acadêmico real.

**Site público:** https://segurancasistemasinternet.github.io/site-alvo/

## Propósito

O site serve como **alvo autorizado de espelhamento com o WinHTTrack**. Sua
publicação no GitHub Pages permite que os alunos copiem uma página a partir de
uma URL pública com HTTPS, em vez de um servidor local, tornando o exercício
mais próximo do acesso a um site na internet.

A atividade demonstra como um web crawler baixa HTML e CSS e segue links
internos para produzir uma cópia estática. O objetivo é **entender a mecânica
do phishing para reconhecer e evitar golpes**, não coletar credenciais nem
imitar uma instituição real.

## Atividade original

Este site é material de apoio do laboratório mantido no repositório
**[SegurancaSistemasInternet/laboratorio-phishing](https://github.com/SegurancaSistemasInternet/laboratorio-phishing)**.
Consulte o [roteiro original da atividade](https://github.com/SegurancaSistemasInternet/laboratorio-phishing/blob/main/README.md)
para preparar o ambiente, configurar o WinHTTrack, aplicar as marcações de treino
e realizar a análise defensiva.

Os dois repositórios têm papéis distintos:

- **Este repositório (`site-alvo`):** contém o portal fictício original,
  publicado e mantido pelo professor.
- **[Repositório da atividade](https://github.com/SegurancaSistemasInternet/laboratorio-phishing):**
  contém o roteiro, os guias de apoio e uma versão de treino marcada, com
  formulário educativo que descarta os dados digitados.

No exercício, os alunos devem **espelhar a URL pública com o WinHTTrack**,
e não clonar este repositório com Git para obter a cópia do site.

## Limites de uso e segurança

- O escopo autorizado é apenas este portal fictício e seus arquivos, dentro de
  `https://segurancasistemasinternet.github.io/site-alvo/`.
- Não use a atividade para copiar a identidade de instituições reais, coletar
  dados ou enviar mensagens enganosas.
- O formulário do alvo é demonstrativo: **não envia dados nem autentica
  usuários**. Mesmo assim, use somente dados fictícios; nunca digite senhas reais.
- Uma cópia publicada pelos alunos deve seguir as regras da atividade original:
  faixa visível de **AMBIENTE DE TREINO — PHISHING SIMULADO** e formulário
  educativo sem coleta de dados.
- Ao concluir, os alunos devem despublicar suas cópias de treino. A manutenção
  do alvo original é responsabilidade do professor.

## Arquivos e publicação

- [index.html](./index.html): página inicial com o formulário demonstrativo.
- [sobre.html](./sobre.html): explicação do caráter fictício e didático do portal.
- [css/estilo.css](./css/estilo.css): estilos compartilhados pelas páginas.

O GitHub Pages publica a raiz da branch `main`. O alvo é estático, sem backend
de autenticação. O HTTPS protege a conexão, mas **não é prova de legitimidade**:
essa distinção faz parte da análise proposta no laboratório.
