# SPASE Connect (Speed Parts & Service Connect)

> **Status do Projeto:** 🚀 Em Desenvolvimento / Pré-Incubação
> **Tipo:** Marketplace B2B2C Automotivo
> **Empresa:** Aksurim Software

## 📋 Sobre o Projeto

O **SPASE Connect** é uma plataforma de marketplace projetada para revolucionar o setor de autopeças e serviços automotivos. A solução resolve a fragmentação do mercado conectando **Clientes Finais**, **Lojistas/Oficinas** e **Distribuidores** em um ecossistema unificado.

Diferente de e-commerces tradicionais, o SPASE Connect integra a compra da peça com o **agendamento garantido do serviço de instalação**, utilizando algoritmos de previsão de tempo e gestão de estoque distribuído.

---

## 🛠 Arquitetura e Engenharia de Software

[cite_start]O projeto foi concebido utilizando uma **Arquitetura de Microsserviços** para garantir escalabilidade horizontal, dado o volume projetado de transações e usuários simultâneos[cite: 61].

### Destaques Técnicos do Escopo:

* [cite_start]**Modelo de Negócio:** Freemium com monetização via Pay-Per-Lead (PPL) e Comissionamento (Split de Pagamento)[cite: 56, 117].
* [cite_start]**Segurança de Dados:** Implementação de protocolos para anonimização de dados geográficos de usuários, em conformidade com a LGPD[cite: 62, 132].
* [cite_start]**Sincronização Real-Time:** Sistema de agendamento que sincroniza inventário físico do lojista com a disponibilidade de agenda (Mão de obra)[cite: 63].

---

## 📱 Módulos e Funcionalidades

O sistema é dividido em três grandes frentes de aplicação:

### 1. App Cliente Final (B2C)
Focado na experiência do usuário e conversão rápida.
* [cite_start]**Minha Garagem (Scan de Placa):** Integração para consulta de dados do veículo via placa para garantir compatibilidade total das peças (Fitment)[cite: 80].
* [cite_start]**Motor de Busca Unificado:** Filtragem avançada por Preço, Avaliação e Distância[cite: 82, 83].
* [cite_start]**Core Loop:** Compra da peça + Agendamento do serviço em uma única transação (Checkout transparente)[cite: 52].

### 2. Painel do Lojista & Oficina (B2B)
Focado em gestão operacional e previsibilidade de receita.
* [cite_start]**Gestão de Catálogo Inteligente:** Cadastro de peças vinculado ao "Tempo Previsto de Instalação" (com buffer de segurança)[cite: 99, 100].
* [cite_start]**Dashboard de Ordens de Serviço:** Visualização estilo "TV Dashboard" para gestão de fluxo de oficina[cite: 105].
* [cite_start]**Geolocalização de Demanda:** Mapa de calor (Heatmap) anonimizado mostrando regiões com maior busca por serviços específicos[cite: 111].

### 3. Back-Office (Administrativo)
* [cite_start]**Gestão Financeira:** Controle de Split de Pagamentos e sistema de créditos pré-pagos para leads (PPL)[cite: 117].
* [cite_start]**Anti-Fraude:** Algoritmos de *cooldown* para evitar fraudes de cliques repetitivos no sistema de créditos[cite: 112].

---

## 📊 Desafio de Negócio (O Problema)

O mercado atual sofre com:
1.  [cite_start]**Agendamento Caótico:** Flutuação de demanda e "dias vazios" nas oficinas[cite: 42].
2.  [cite_start]**Desconexão Venda/Serviço:** O cliente compra a peça na internet, mas não encontra quem instale ou a peça chega errada[cite: 48].
3.  [cite_start]**Estouro de Prazo:** Dificuldade das oficinas em estimar o tempo real de serviço[cite: 43].

[cite_start]**Solução SPASE:** Centraliza a jornada em uma experiência 3-em-1: Cotação Rápida + Compra/Agendamento + Garantia[cite: 50].

---

## 🔒 Aviso de Propriedade Intelectual

Este repositório serve como **documentação pública** do portfólio de Engenharia de Software e Produto de **Joannderson Lucena**.

O código-fonte do **SPASE Connect** é privado e protegido, pois trata-se de um ativo intelectual da **Aksurim Software** atualmente em processo de pré-incubação e validação de mercado.

---

<div align="center">
  Desenvolvido por <strong>Aksurim Software</strong>
</div>

---

<div align="center">Copyright © 2024 Aksurim Software. Todos os direitos reservados.</div>

### 📫 Contato

**Joannderson Lucena**
* **Role:** Founder & Lead Developer / Product Owner
* **LinkedIn:** [linkedin.com/in/joanndersonlucena](https://www.linkedin.com/in/joanndersonlucena)
* **Email:** joanndersonlucena@hotmail.com
