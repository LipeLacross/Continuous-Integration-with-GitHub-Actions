## 🌐 [English Version of README](README_EN.md)

# Continuous-Integration-with-GitHub-Actions

This project aims to provide a collection of guides and practical examples for setting up and using GitHub Actions in continuous integration and automated deployment processes. Through this repository, you will find detailed instructions to prepare the environment, configure workflows, use triggers, and manage variables and secrets.

## 🔨 Project Features

- Configuration and automation of workflows with GitHub Actions.
- Practical examples of triggers: on_push, on_pull_request, on_workflow_dispatch, on_cron, among others.
- Demonstration of the use of variables, secrets, and matrix strategies.
- Comprehensive documentation to assist in implementing CI/CD.

### Visual Example of the Project
*Insert an image or link to a visual example of the project.*

## ✔️ Techniques and Technologies Used

- GitHub Actions
- YAML (for defining workflows)
- Git (version control)

## 📁 Project Structure

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

## 🛠️ Open and Run the Project

2. **Clone the Repository**:
    - Copy the repository URL and execute the command below in your terminal:

   ```bash
   git clone <REPOSITORY_URL>
   ```

## 🌐 Deploy

To deploy the project, follow the steps below:

1. **Configure Environment Variables and Secrets**:
    - Access the repository settings on GitHub and add the necessary secrets (e.g., tokens, API keys) in the "Secrets" section.

2. **Check the Deployment Workflow File**:
    - Ensure that the workflow file (for example, `deploy.yml`) is properly configured with the necessary steps for deploying your environment.

3. **Push to the Branch Configured for Deployment**:
    - Usually, pushing to the main branch (main/master) or a specific branch will automatically trigger the deployment workflow via GitHub Actions.

4. **Monitor the Deployment Process**:
    - Check the GitHub Actions logs to ensure that the deployment process was successfully executed and to identify any potential errors.
