# 🚗 AutoMechMind

> **Sistema inteligente de gestão para oficinas mecânicas**  
> Gestão de clientes, orçamentos e ordens de reparação numa aplicação desktop moderna e modular.

---

## ✨ Visão Geral

O **AutoMechMind** é uma aplicação desktop desenvolvida para simplificar e centralizar a gestão de uma oficina mecânica.

O foco do projeto está em:
- Resolver problemas reais do dia a dia
- Manter uma arquitetura limpa e escalável
- Demonstrar boas práticas de engenharia de software

Este repositório foi preparado com especial atenção para **avaliação técnica por recrutadores**.

---

## 🖥️ Interface da Aplicação

### Menu Principal
![Menu Principal](./menu.png)

### Orçamentos
![Orçamentos](./quote.png)

### Ordens de Reparação
![Ordens de Reparação](./orderRepair.png)

### Edição de Cliente
![Edição de Cliente](./editclient.png)

### Definições do Sistema
![Definições](./definitions.png)

---

## 🧠 Funcionalidades Principais

- 📋 **Gestão de Clientes**  
  Criação, edição e consulta de clientes de forma simples e rápida.

- 💰 **Orçamentos**  
  Criação de orçamentos detalhados, com possibilidade de evolução para ordens de reparação.

- 🔧 **Ordens de Reparação**  
  Acompanhamento do estado dos serviços realizados.

- ⚙️ **Definições Centralizadas**  
  Configuração do sistema num único local.

- 🧱 **Arquitetura Modular**  
  Código organizado por camadas, facilitando manutenção e evolução futura.

---

## 🏗️ Arquitetura do Projeto

O projeto segue os princípios da **Clean Architecture**, com separação clara de responsabilidades e dependências sempre direcionadas para o núcleo do sistema:

- **Entities**  
  Contêm as entidades e regras de negócio fundamentais.  
  São independentes de qualquer framework ou detalhe externo.

- **Use Cases**  
  Implementam a lógica da aplicação e os casos de uso do sistema.  
  Orquestram o fluxo entre entidades, sem dependência da UI ou infraestrutura.

- **Controllers**  
  Atuam como adaptadores entre a interface e os casos de uso.  
  Recebem inputs da UI, validam e encaminham para os *use cases*.

- **Frameworks**  
  Camada mais externa, responsável por detalhes técnicos como UI, bibliotecas e integrações.  
  Depende das camadas internas, nunca o contrário.

Esta abordagem permite:
- Melhor legibilidade do código
- Facilidade de testes
- Evolução incremental do sistema

---

## 🛠️ Tecnologias Utilizadas

- **C++**
- **Qt Framework**
- Programação orientada a objetos
- Princípios de arquitetura limpa
- Organização modular do código

---

## 🎯 Objetivo do Projeto

O **AutoMechMind** foi desenvolvido para demonstrar:

- Capacidade de desenvolver aplicações desktop reais
- Organização de projetos de média dimensão
- Boas práticas de arquitetura e manutenção
- Atenção à experiência do utilizador

É um projeto representativo de um cenário profissional.

---

## 🚀 Roadmap (Evolução Futura)

- 🧪 Testes automatizados
- 🌐 Expansão multiplataforma

---

## 👤 Autor

Projeto desenvolvido no contexto de evolução técnica em **engenharia de software e aplicações desktop**.

> 📌 Este repositório foi estruturado para facilitar análise técnica por recrutadores.

---

⭐ Se este projeto foi útil ou interessante, considera deixar uma estrela! Se tiveres interesse em adquirir contacta: pedrodaniel17.0750@gmail.com
