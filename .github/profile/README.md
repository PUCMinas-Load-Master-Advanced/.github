# Bem-vindos à Organização **PUCMinas Load Master-Advanced** (Sistemas Embarcados do Planador)

Este espaço é dedicado ao desenvolvimento de firmware e eletrônica do **Planador** no
projeto **LoadMaster Advanced** (Classe Advanced - SAE AeroDesign),
desenvolvido pela **PUC Minas – Unidade São Gabriel**.

## Sobre o Projeto

Nosso objetivo é projetar, construir e integrar o sistema de controle e telemetria do
planador. Isso inclui:
- Firmware em C/C++ para leitura de sensores, gravação de dados (DAS) e/ou navegação autônoma (HUD, pouso autônomo).
- Integração de componentes eletrônicos: MCUs, barramentos (I2C, SPI, UART), baterias e módulos de RF (se necessário).
- Geração de logs e telemetria para análise pós-voo.

> **Observação**: O planejamento detalhado (sprints, cronogramas, etc.) é gerenciado nas issues,
projetos ou GitHub Actions desta organização.

## Repositórios Principais

- **planador-firmware-embedded**: Código-fonte (C/C++), drivers, testes unitários, scripts de build.
- **planador-hardware-design**: Arquivos de PCB e esquemas (KiCad/Altium) para o sistema embarcado.
- **planador-docs-embedded**: Documentação técnica, manuais de integração, logs de ensaios.
- **planador-test**: Testes de integração e validação (HIL, cenários avançados, logs).
- **planador-tools-embedded**: Scripts e utilitários (build, flash, logs) para suporte ao desenvolvimento.
- **planador-simulation**: Modelos e simulações de voo (SIL/Simulink/Gazebo).
- **planador-telemetry**: Coleta, análise e visualização de dados de voo.
- **planador-prototypes**: Projetos experimentais para testes rápidos e provas de conceito.
- **planador-ci**: Infraestrutura de CI/CD (pipelines, build, testes automáticos).


## Como Contribuir

1. Faça um fork ou crie uma branch no repositório correspondente (por exemplo, `planador-firmware`).
2. Abra uma **Issue** para relatar problemas ou sugerir melhorias.
3. Submeta um **Pull Request**, incluindo descrição, testes realizados e impacto esperado.

## Contato

- Para dúvidas, abra uma Issue ou converse com a equipe responsável pelo firmware do planador via Teams/Discord/e-mail.
- Informações gerais do projeto LoadMaster Advanced podem ser encontradas em outros repositórios ou nos canais oficiais da equipe.

---
**Obrigado por apoiar o desenvolvimento do Planador no projeto LoadMaster Advanced!**
Junte-se a nós para construir soluções embarcadas robustas e inovadoras.
