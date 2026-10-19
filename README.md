# infra-como-codigo

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-C9A84C)
![Licença MIT](https://img.shields.io/badge/licen%C3%A7a-MIT-green)

**[English below](#english)**

**Infraestrutura como código** para subir um servidor completo a partir de arquivos versionados: rede e firewall com **Terraform** (Hetzner Cloud), configuração inicial com **cloud-init**, ajustes com **Ansible** e serviços com **Docker Compose**.

## Por que este projeto

Servidor criado à mão vira um servidor que ninguém sabe recriar. Com tudo em código, o ambiente pode ser revisado, versionado e reconstruído do zero em minutos — inclusive monitoramento e backup.

## O que está a caminho

O projeto está sendo construído em entregas pequenas, cada uma com testes e CI. Acompanhe pelos commits e pull requests.

- [ ] Módulo Terraform de servidor com firewall, chave SSH e volume
- [ ] cloud-init de base (usuário, SSH, atualizações)
- [ ] Stack de monitoramento em Docker Compose
- [ ] Playbook que instala o backup-restic-r2

## Tecnologias

Terraform · cloud-init · Ansible · Docker Compose · tflint · GitHub Actions

## Autor

**Euller Pinheiro**, Diretor Técnico da [ESX Tecnologia](https://esxtecnologia.com) — desenvolvimento de sistemas, infraestrutura e TI gerenciada em São Paulo.

---

<a name="english"></a>
## English

Infrastructure as code to rebuild a full server from versioned files: Terraform on Hetzner Cloud, cloud-init, Ansible and Docker Compose stacks for monitoring and backup. Work in progress — built in small, tested increments. Licensed under [MIT](LICENSE).
