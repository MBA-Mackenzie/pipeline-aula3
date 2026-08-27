# Projeto de Automação CI/CD

Este repositório demonstra como configurar **pipelines de Integração Contínua (CI)**, **Entrega Contínua (CD)** e um fluxo **CI/CD completo** utilizando **GitHub Actions**.

---

## Objetivos
- Mostrar como configurar workflows simples de CI para validação de código.
- Demonstrar um pipeline de CD para deploy automático.
- Integrar CI e CD em um pipeline único de CI/CD.

---

##  Configuração inicial

Clone o repositório e configure o remoto:

```bash
git clone https://github.com/MBA-Mackenzie/pipeline-aula3.git
cd pipeline-aula3

echo "# pipeline-aula3" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/MBA-Mackenzie/pipeline-aula3.git
git push -u origin main
