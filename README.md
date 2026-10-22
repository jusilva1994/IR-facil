# 📊 IR-Fácil — Gestão e Organização para Imposto de Renda

O **IR-Fácil** é uma ferramenta de gestão financeira em Excel desenvolvida para simplificar e organizar o recolhimento de informações essenciais para a Declaração do Imposto de Renda de Pessoa Física (IRPF).

Com uma interface intuitiva, botões de navegação rápida entre abas e fórmulas automatizadas, a planilha permite centralizar dados cadastrais, informes bancários, extratos de receitas e consultas de tabelas institucionais em um único local.

---

## 🚀 Funcionalidades Principais

* **Cadastro Centralizado:** Registro completo dos dados do titular, dependentes/cônjuge e endereço.
* **Controle de Informes Bancários:** Consolidação de saldos e comprovantes de rendimentos por instituição financeira com somatório automático.
* **Registro de Entradas e Holerites:** Apuração detalhada mês a mês das receitas e entradas financeiras categorizadas.
* **Tabelas Auxiliares e Validação:** Lista padronizada de instituições financeiras para evitar erros de digitação.
* **Navegação Dinâmica por Botões:** Menu interativo integrado que substitui a navegação tradicional por abas inferiores.

---

## 📂 Estrutura das Planilhas (Abas)

A pasta de trabalho está dividida em **4 módulos (abas)** interligados:

| Aba | Nome na Planilha | Descrição |
| :--- | :--- | :--- |
| 👤 **1** | `TITULAR` | Armazena dados pessoais do contribuinte (Nome, CPF, Data de Nascimento, Título de Eleitor, Cônjuge, Endereço, CEP e Contato). |
| 🏦 **2** | `INFORMES` | Registra os informes de rendimentos bancários (Itaú, PicPay, etc.), saldos atuais e atalhos/nomes de anexos em PDF, calculando o total consolidado (`SUM`). |
| 💵 **3** | `NOTAS` | Lançamento temporal (mês a mês) das receitas de holerites e notas financeiras de entrada, com data, categoria e valor. |
| 📑 **4** | `TABELAS` | Tabela de suporte contendo códigos e nomes oficiais das instituições bancárias (ex: Itaú, Caixa, BB, BTG, Stone) utilizada na validação de dados. |

---

## 🔘 Dinâmica dos Botões de Navegação entre Planilhas

Para proporcionar uma experiência de uso semelhante à de um sistema desktop/web, a planilha conta com um **Menu Interativo de Navegação Superior** presente em todas as abas.

### 💡 Como Funciona?

1. **Hiperlinks Internos / Vínculos de Célula:**
   Cada botão é vinculado diretamente a uma célula de referência no cabeçalho da aba de destino (por exemplo, o botão `NOTAS` aponta para o endereço `#NOTAS!A1`).
2. **Navegação em Um Clique:**
   Ao clicar sobre o botão desejado no menu superior:
   * A visualização da planilha é alterada instantaneamente para a aba correspondente.
   * O cursor é posicionado automaticamente no topo da página (`A1`), mantendo o padrão visual e a fluidez de navegação.
3. **Indicador de Aba Ativa:**
   Os botões possuem destaques visuais (cores e bordas diferenciadas) para indicar qual aba está ativa no momento, facilitando a orientação do usuário.

---

## 🛠️ Como Utilizar a Planilha

1. **Preenchimento dos Dados Pessoais (`TITULAR`):**
   * Abra a planilha e preencha todos os campos do titular e cônjuge para manter o cadastro atualizado.
2. **Lançamento de Informes Bancários (`INFORMES`):**
   * Informe o banco (utilize a lista suspensa integrada à aba `TABELAS`), insira o valor acumulado e o nome/caminho do arquivo do informe em PDF.
   * O somatório geral é atualizado automaticamente no topo da seção.
3. **Lançamento de Receitas (`NOTAS`):**
   * Registre as entradas financeiras informando data, categoria (ex: `HOLERITE`) e valor correspondente.
4. **Navegação:**
   * Utilize os botões do menu superior para alternar entre as telas de forma rápida e prática.

---

## 📦 Requisitos do Sistema

* **Microsoft Excel 2016** ou superior (compatível com Excel 365, Excel Online e Google Planilhas).

---
