## 🌐 [English Version of README](README_EN.md)

# Continuous-Integration-with-GitHub-Actions

Este projeto tem como objetivo fornecer uma coleção de guias e exemplos práticos para a configuração e utilização do GitHub Actions em processos de integração contínua e deploy automatizado. Através deste repositório, você encontrará instruções detalhadas para preparar o ambiente, configurar workflows, utilizar triggers e gerenciar variáveis e segredos.

## 🔨 Funcionalidades do Projeto

- Configuração e automação de workflows com GitHub Actions.
- Exemplos práticos de triggers: on_push, on_pull_request, on_workflow_dispatch, on_cron, entre outros.
- Demonstração do uso de variáveis, segredos e estratégias de matrix.
- Documentação completa para auxiliar na implementação de CI/CD.

## ✔️ Técnicas e Tecnologias Utilizadas

- GitHub Actions
- YAML (para definição de workflows)
- Git (controle de versão)

## 📁 Estrutura do Projeto

```plaintext
|-- LICENSE
|-- README.md
|-- README_EN.md
|-- guia_aulas/
  |-- 1_preparando_ambiente/
    |-- 1_instalacao.md
    |-- 2_chave_ssh.md
    |-- 3_config_global.md
    |-- 4_instalacao_vs_code.md
    |-- 5_criando_repositorio.md
  |-- 2_introducao_github_actions/
    |-- 1_o_que_e_github_actions.md
    |-- 2_workflow_templates.md
    |-- 3_estrutura_basica.md
    |-- 4_sintaxe_variaveis.md
  |-- 3_gatilhos_de_execucao/
    |-- 1_documentacao_triggers.md
    |-- 2_on_push.md
    |-- 3_on_pull_request.md
    |-- 4_on_workflow_dispatch.md
    |-- 5_on_cron.md
    |-- 6_on_workflow_run.md
  |-- 4_senhas_variaveis/
    |-- 1_config_variaveis_gha/
      |-- 1_config_variaveis_gha.md
      |-- 1_config_variaveis_gha.yml
    |-- 2_config_secrets_gha/
      |-- 2_config_secrets_gha.md
      |-- 2_config_secrets_gha.yml
    |-- 3_variavel_ambiente/
      |-- 3_variavel_ambiente.md
      |-- 3_variavel_ambiente.yml
  |-- 5_variacoes_workflows/
    |-- 1_dependecia_job/
      |-- 1_dependecia_job.md
      |-- 1_dependecia_job.yml
    |-- 2_matrix_strategy/
      |-- 2_matrix_strategy.md
      |-- 2_matrix_strategy.yml
    |-- 3_condicionais/
      |-- 3_condicionais.md
      |-- 3_condicionais.yml
    |-- 4_gerenciamento_erros/
      |-- 4_gerenciamento_erros.md
      |-- 4_gerenciamento_erros.yml
```

## 🛠️ Abrir e rodar o projeto

2. **Clone o Repositório**:
    - Copie a URL do repositório e execute o comando abaixo no terminal:

   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```

## 🌐 Deploy

Para fazer o deploy do projeto, siga os passos abaixo:

1. **Configure as variáveis de ambiente e segredos**:
    - Acesse as configurações do repositório no GitHub e adicione os segredos necessários (ex.: tokens, chaves de API) na seção "Secrets".

2. **Verifique o arquivo de workflow de deploy**:
    - Certifique-se de que o arquivo de workflow (por exemplo, `deploy.yml`) está configurado corretamente com os passos necessários para o deploy do seu ambiente.

3. **Realize um push para a branch configurada para deploy**:
    - Geralmente, um push para a branch principal (main/master) ou uma branch específica acionará automaticamente o workflow de deploy pelo GitHub Actions.

4. **Monitore o processo de deploy**:
    - Verifique os logs do GitHub Actions para garantir que o processo de deploy foi executado com sucesso e identifique possíveis erros.

```
