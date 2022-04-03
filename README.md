## Table of Contents
1. [Ansible](#Ansible)
2. [Terraform](#Terraform)
3. [GitLab](#GitLab)
4. [Kubernetes](#Kubernetes)
5. [DevOps](#DevOps)

## Ansible

#### What is it
[Ansible](https://docs.ansible.com/) é uma ferramenta de automação utilizada para gerência de configuração, deploy de aplicações, e provisionamento de infraestrutura. É extremamente utlizado em ambientes com centenas de servidores. A comunicação é feita através do protocolo `SSH` sem a necessidade de agentes instalados no hosts remotos. Use o Ansible para instalar softwares, automatizar tarefas rotineiras, provisionar infraestrutura, melhorar a segurança dos ativos, aplicar patching em sistemas e compartilhar automação em seu projeto/trabalho/estudos.

#### Main concepts
- [ ] *Ad-hoc*: é um comando ou automação fornecida pelo Ansible para gerenciamento de configuração através da CLI do LINUX.
- [ ] *Playbooks*: é um conjunto de tasks ou tarefas descritas no formato *YML*.
- [ ] *Roles*: é uma estrutura de diretórios organizada de forma lógica para utilização em projetos complexos.
- [ ] *inventory file*: arquivo utilizado para gerenciamento dos hosts que o Ansible vai afetar.
- [ ] *ansible.cfg*: principal arquivo de configuração do Ansible para gerenciar o modo de uso da ferramenta.
- [ ] *modules*: são os métodos escritos em *Python* que o Ansible usa para abstração de comandos (são usados para realizar tarefas de automação).

#### How it helps
Basicamente o *Ansible* ajuda a manter todo o gerenciamento de configuração da sua infraestrutura de forma simples e consistente. O gerenciamento de configuração é o processo usado para manter sistemas computacionais, servidores e softwares em um estado desejado, consistentemente. É uma forma de se certificar de que o sistema funciona como o esperado enquanto as mudanças são feitas. Tradicionalmente, isso é feito de forma manual ou por meio de scripts personalizados criados por administradores de sistemas. Quando o Ansible é usado como uma ferramenta de gerenciamento de configuração, ele ajuda a armazenar e auxiliar na manutenção do estado atual dos sistemas. 


## Terraform

#### What is it
[Terraform](https://www.terraform.io/) é uma ferramenta de *Infrastructure as Code (IaC)*, utilizada para provisionamento de infraestrutura em diversos *providers*, como, AWS, Azure, Google Cloud, Kubernetes, GitLab e outros. Essa abordagem de *IaC* vem sendo muito empregada pelo mercado para você manter sua infraestrutura via código, sendo gerenciada e mantida através do *Git*. Sua infraestrutura é escrita via Terraform usando uma linguagem de configuração declarativa conhecida como *HashiCorp Configuration Language* ou *HCL*.

#### Main concepts
- [ ] *providers*: é o bloco onde você declara qual é o seu *provider* ou produto que você pretende provisionar a infraestrutura ou serviços.
- [ ] *resources*: é o bloco onde você declara um ou mais objetos/recuros da infraestrutura, como exemplo, redes virtuais, instâncias de computação e/ou componentes de armazenamento.
- [ ] *tfstate*: arquivo usado pelo Terraform para gerenciamento do estado da infraestrutura, aqui nesse arquivo que o Terraform sabe o que foi aplicado ou destruído da infraestrutura.
- [ ] *modules*: é o bloco usado para você declarar módulos para o Terraform, os módulos ajudam a deixar seu projeto de Terraform mais organizado, menos complexo e menos repetição de código.

#### How it helps
O Terraform ajuda você a manter a infraestrutura de rede de forma segura e eficiente, pois ele consegue gerenciar o estado da mesma, ou seja, ele entende o que você esta aplicando e quando pretender destruir, ele também saberá o que remover. O Terraform é capaz de determinar o que mudou e criar planos de execução incrementais que podem ser aplicados no seu ambiente. O Terraform é desenvolvido e mantido pela empresa Hashicorp. Ele é gratuito com código fonte aberto e você pode efetuar contribuições na comunidade através do GitHub.

## DevOps

#### What is it
asasas

#### Main concepts
sas

#### How it helps


