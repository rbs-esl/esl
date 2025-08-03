# Visão Geral do Projeto: [Nome do seu Projeto - Ex: Infraestrutura Meu Librechat]

Este projeto foca na implantação e gerenciamento de uma infraestrutura para o aplicativo "Librechat" na Google Cloud Platform. Ele inclui serviços web, bancos de dados e, potencialmente, componentes personalizados de machine learning.



## Diretivas para o Gemini:

**1. Idioma e Comunicação:**
*   **Idioma de Interação:** Sempre responda a perguntas diretas e interaja com o usuário em **Português do Brasil**.
*   **Idioma Técnico (Código/Comandos):** Todos os snippets de código, comentários dentro do código, instruções de linha de comando e explicações técnicas devem ser fornecidos em **Inglês**.

**2. Contexto do Projeto e Tecnologias Principais:**
*   **Base do Código:** Analise minuciosamente todo o diretório do projeto e os subdiretórios relevantes. O projeto está estruturado da seguinte forma:
    *   `/src/backend`: Contém o código Python (Flask/FastAPI) para a API.
    *   `/src/frontend`: Contém o código do frontend (React/Angular/Vue.js).
    *   `/infra/gcp`: Contém configurações de infraestrutura como código (IaC) usando Terraform/Pulumi.
    *   `/docs`: Contém documentação adicional do projeto.
*   **Linguagens de Programação:** As linguagens primárias usadas são **Python 3.10+**, **JavaScript (ES6+)** e **TypeScript**. Para infraestrutura, **HCL (Terraform)**.
*   **Frameworks e Bibliotecas Chave:**
    *   **Backend:** FastAPI, SQLAlchemy, Pydantic.
    *   **Frontend:** React, Redux, Material-UI.
    *   **Testes:** Pytest, Jest.
*   **Serviços Google Cloud Utilizados:**
    *   **Computação:** Cloud Run (para APIs), Cloud Functions (para funções serverless).
    *   **Banco de Dados:** Cloud SQL para PostgreSQL.
    *   **Armazenamento:** Cloud Storage (para arquivos estáticos e uploads).
    *   **Rede:** Cloud Load Balancing, VPC.
    *   **CI/CD:** [Mencione sua ferramenta de CI/CD se for relevante, ex: Cloud Build, GitHub Actions].

**3. Melhores Práticas e Padrões de Qualidade:**
*   **Adesão a Padrões:** Para código Python, siga estritamente as diretrizes da **PEP 8**. Para JavaScript/TypeScript, siga as configurações do nosso `.eslintrc.json`.
*   **Segurança:** Priorize sempre soluções seguras. Ao propor arquiteturas GCP, considere o **Princípio do Menor Privilégio (PoLP)** para IAM.
*   **Eficiência e Otimização:** Sugira soluções que sejam escaláveis, eficientes em termos de custo e otimizadas para desempenho.
*   **Observabilidade:** Ao discutir implantações ou depuração, inclua sugestões para logging (Cloud Logging) e monitoramento (Cloud Monitoring).

**4. Fluxo de Trabalho e Expectativas de Resposta:**
*   **Depuração e Resolução de Problemas:** Ao analisar erros, forneça um diagnóstico claro, uma explicação da causa raiz e um conjunto de ações corretivas passo a passo.
*   **Geração de Código:** Para trechos de código, forneça exemplos completos e executáveis sempre que possível, com comentários explicativos.
*   **Gerenciamento de Código Fonte:** O código deste projeto é gerenciado no **GitHub** (https://github.com/[seu-usuario-github]/[seu-repo-github]). Considere o GitHub como a fonte da verdade para o controle de versão.
*   **Contexto Organizacional GCP:** Este projeto faz parte da Organização GCP vinculada ao domínio `rbsesl.lat` (gerenciada via Cloud Identity Free Edition). Ao discutir políticas de IAM, governança ou recursos de nível de Organização, leve em conta essa estrutura.
*   **Ferramentas e Autonomia:** Aproveite sua capacidade de acessar a internet (via `cloudaicompanion.codeToolsUser` para informações atualizadas) e de interagir com o ambiente Google Cloud (via `cloudasset.viewer`) para obter contexto relevante.

**5. Personalização do `GEMINI.md`:**
*   Este arquivo é dinâmico. Na interação inicial ou quando solicitado, revise este `GEMINI.md`.
*   Com base na sua análise contínua do código e do meu fluxo de trabalho de desenvolvimento, proponha **adições ou modificações** a este arquivo que aprimorariam sua capacidade de me auxiliar neste projeto.
*   Apresente as mudanças propostas como um bloco de conteúdo `GEMINI.md` completo e atualizado para minha revisão.
