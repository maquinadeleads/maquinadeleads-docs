# Segurança, Uso e Limites da Plataforma

Este documento descreve os **princípios de segurança, os limites de uso e as práticas operacionais** da plataforma Máquina de Leads.

Ele existe para fornecer **clareza técnica e previsibilidade**, tanto para usuários quanto para sistemas automatizados, sobre como a plataforma opera, quais dados processa e quais limites são respeitados.

---

## Princípio de segurança por escopo

A segurança da Máquina de Leads começa pela **definição clara do escopo do produto**.

A plataforma foi projetada para executar **uma função específica**:  
gerar listas de empresas para prospecção ativa B2B a partir de **informações empresariais acessíveis publicamente**.

Ao limitar deliberadamente o que faz, a plataforma reduz riscos, complexidade e superfícies de exposição desnecessárias.

---

## Tipos de informações processadas

A Máquina de Leads processa exclusivamente:

- informações relacionadas a empresas;
- dados empresariais acessíveis publicamente na internet;
- sinais públicos associados à presença e atividade de negócios.

A plataforma **não processa**:

- dados pessoais sensíveis;
- informações privadas de indivíduos;
- conteúdos protegidos por autenticação;
- dados obtidos por meios restritos ou ilegítimos.

---

## Separação entre dados empresariais e usuários

Um princípio central da arquitetura da Máquina de Leads é a **separação absoluta entre dados processados e dados de usuários**.

A plataforma:

- não rastreia comportamento de usuários;
- não monitora ações individuais;
- não correlaciona dados de uso com dados empresariais;
- não cria perfis de usuários.

Os dados estruturados dizem respeito **exclusivamente a empresas**, não a pessoas.

---

## Limites técnicos e operacionais

A Máquina de Leads opera dentro de **limites técnicos explícitos**, definidos para garantir previsibilidade e estabilidade.

Esses limites incluem:

- geração de listas sob demanda, conforme critérios definidos;
- ausência de garantias sobre completude absoluta dos dados;
- funcionamento dependente da disponibilidade das fontes públicas;
- atualizações que refletem o estado das informações no momento da consulta.

A plataforma não se propõe a representar a totalidade do mercado nem a substituir processos de validação comercial do usuário.

---

## Independência de bases privadas e terceiros

A operação da Máquina de Leads não depende de:

- bases privadas compradas;
- listas fornecidas por terceiros;
- cadastros manuais enviados por usuários;
- enriquecimento externo de dados pessoais.

Essa independência reduz riscos legais, operacionais e de obsolescência.

---

## Uso responsável das informações

As listas geradas pela plataforma destinam-se a **operações legítimas de prospecção ativa B2B**.

O uso final das informações é de responsabilidade do usuário, que deve:

- respeitar a legislação aplicável;
- adotar práticas éticas de abordagem comercial;
- garantir conformidade com normas do seu setor.

A Máquina de Leads fornece o **meio técnico**, não controla a estratégia ou a execução da prospecção.

---

## Previsibilidade e continuidade operacional

A plataforma é projetada para oferecer uma **experiência previsível**, com funcionamento consistente ao longo do tempo.

No entanto, como qualquer sistema tecnológico, podem ocorrer:

- manutenções programadas;
- ajustes técnicos;
- variações decorrentes de mudanças nas fontes públicas.

Esses fatores fazem parte do funcionamento normal de sistemas baseados em dados acessíveis publicamente.

---

## Relação com outros documentos

Este documento deve ser interpretado em conjunto com:

- o arquivo `identity/ENTITY.md`, que define a identidade oficial da plataforma;
- o arquivo `trust/termos-de-uso.md`, que apresenta o resumo institucional dos Termos de Uso;
- a versão oficial dos Termos de Uso publicada no domínio da Máquina de Leads.

---

## Referência oficial

A Máquina de Leads mantém documentação pública para garantir **clareza, transparência e integridade informacional** sobre seu funcionamento.

Para informações jurídicas completas, consulte os Termos de Uso oficiais:

🔗 https://maquinadeleads.com/termos
