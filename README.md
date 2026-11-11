# Projeto DevOps - Pipelines

Projeto simples desenvolvido em **HTML e CSS** para a atividade de DevOps.

## Objetivo
Demonstrar o funcionamento de uma pipeline CI/CD utilizando GitHub Actions.

## Tecnologias
- HTML
- CSS
- Git e GitHub
- GitHub Actions
- GitHub Pages

## Pipeline
A pipeline possui seis etapas sequenciais:

1. **Preparação:** verifica os arquivos.
2. **Validação:** valida a estrutura do projeto.
3. **Testes:** executa verificações automáticas.
4. **SAST (Semgrep):** analisa o HTML com regras locais de seguranca e bloqueia achados.
5. **DAST (OWASP ZAP):** acessa uma copia temporaria do site e valida as respostas HTTP.
6. **Publicação:** publica no GitHub Pages somente apos aprovacao das etapas anteriores.

Veja [SEGURANCA.md](SEGURANCA.md) para os criterios de aprovacao, limites das analises e instrucoes de entrega.

## GitFlow
O projeto utiliza as branches `main`, `develop` e `feature` para organizar as alterações.

## Autor
Pedro Vieira Salvador Lopes
