# 🖥️ Sistema de Cálculo de Folha de Pagamento em Java

Este projeto consiste em um software de console desenvolvido em Java para automatizar o cálculo salarial de colaboradores de acordo com o seu modelo de contratação. O objetivo principal é eliminar processos manuais no Departamento Pessoal, mitigar erros de digitação e garantir a precisão dos cálculos financeiros.

Projeto desenvolvido como parte da entrega prática de Lógica de Programação / Raciocínio Computacional na trilha da **UniSociesc / Ecossistema Ânima**.

---

## 🎯 Funcionalidades Principais

* **Menu Interativo Dinâmico:** Painel em laço contínuo (`do-while`) controlado por estrutura de decisão `switch-case`.
* **Segmentação de Regras de Negócio:** Separação lógica e estrita para três categorias de colaboradores:
  * **Padrão:** Recebe o salário base fixo.
  * **Comissionado:** Calcula o salário somando o percentual de comissão sobre o volume de vendas executado.
  * **Produção:** Calcula o salário somando o bônus por quantidade de unidades produzidas.
* **Persistência de Dados em Memória:** Uso de um `ArrayList` global para armazenar o histórico de todos os colaboradores cadastrados durante a execução.
* **Segurança e Usabilidade:** * Isolamento do salário-base utilizando uma constante global protegida (`private static final`).
  * Formatação monetária padronizada de duas casas decimais utilizando `printf` e `String.format`.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
* Possuir o **Java JDK** (versão 11 ou superior) instalado na máquina.
* Um editor de código (recomendado: **VS Code** com a extensão *Extension Pack for Java*).

### Passo a Passo
1. Clone este repositório no seu ambiente local:
   ```bash
   git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
