<p align="center"><img src="./banner.svg" alt="Igor Wendel, Desenvolvedor Web Full Stack" width="100%"></p>

<p align="center">
Crio sistemas web que substituem controles manuais por fluxos com regras, aprovação e histórico.<br>
Atendo empresas, órgãos e projetos como autônomo.
</p>

<p align="center"><b>Clique em um dos botões para abrir</b></p>

<details>
<summary><b>🟦 SAF · Sistema de Agendamento de Férias</b></summary>
<br>

<a href="https://github.com/Igor-Wendel/SAF"><img src="./painel-saf.svg" alt="Painel ilustrativo do SAF" width="100%"></a>

| O que resolve | Como |
|---|---|
| Férias agendadas fora da regra | Valida período aquisitivo, data limite, venda de dias e antecedência, conforme a CLT |
| Aprovação por e-mail e planilha | Fluxo por perfil: Gestor solicita, RH aprova, DP acompanha |
| Cadastro digitado duas vezes | Sincronização diária com o ERP e login pela conta de rede |
| Posto sem ninguém nas férias | Indica quem cobre e envia a informação ao CGV |

**Tecnologias:** PHP 8 · MariaDB · JavaScript · Docker · Playwright

➡️ [Abrir o repositório do SAF](https://github.com/Igor-Wendel/SAF)

</details>

<details>
<summary><b>🟩 CGV · Controle Geral de Volantes</b></summary>
<br>

<a href="https://github.com/Igor-Wendel/CGV"><img src="./painel-cgv.svg" alt="Painel ilustrativo do CGV" width="100%"></a>

| O que resolve | Como |
|---|---|
| Posto de serviço descoberto | Registra a ausência e mostra quais volantes e intermitentes estão livres |
| Desconto na fatura por posto vazio | Guarda quem cobriu cada posto em cada dia |
| Fechamento do mês feito à mão | Calcula os dias cobertos e não cobertos por contrato |
| Informação espalhada | Dashboard, notificações por perfil e auditoria de cada alteração |

**Tecnologias:** PHP · MariaDB · JavaScript · Docker

➡️ [Abrir o repositório do CGV](https://github.com/Igor-Wendel/CGV)

</details>

<details>
<summary><b>🔗 Como os dois se integram</b></summary>
<br>

```mermaid
flowchart LR
    ERP[(ERP)] -->|colaboradores e férias| SAF
    AD[(Active Directory)] -->|login| SAF
    AD -->|login| CGV
    SAF -->|férias aprovadas| CGV
    CGV -->|pedidos de troca de cobertura| SAF
    SAF -->|e-mails| RH([RH e Gestores])
    CGV -->|notificações| OP([Prepostos e Gestores])
```

</details>

<p align="center">
  <img src="https://skillicons.dev/icons?i=php,js,html,css,mysql,docker,git,gitlab,python&perline=9" alt="PHP, JavaScript, HTML, CSS, MySQL, Docker, Git, GitLab, Python">
</p>

## Sobre mim

- **Desenvolvedor Web Full Stack**, estudante de Ciência da Computação (Estácio).
- Dois sistemas em produção, usados por mais de 30 pessoas para controlar mais de 6.000 colaboradores.
- Do levantamento das regras à implantação: desenvolvimento, testes, segurança e documentação.
- Inglês intermediário.

## Contato

Aberto a oportunidades como desenvolvedor e a projetos como autônomo.

- 📧 **E-mail:** [igor@buildertech.com.br](mailto:igor@buildertech.com.br)
- 📱 **Telefone / WhatsApp:** [+55 61 98423-7453](https://wa.me/5561984237453)

---

<sub>🇺🇸 <b>English:</b> Full stack web developer (PHP, SQL, JavaScript) and Computer Science student. I build web systems that replace manual controls with rule-based, auditable workflows. Two systems in production, used by 30+ people to manage 6,000+ employees: <a href="https://github.com/Igor-Wendel/SAF">SAF</a> (vacation scheduling) and <a href="https://github.com/Igor-Wendel/CGV">CGV</a> (position coverage management for outsourcing companies). Open to developer roles and freelance projects.</sub>
