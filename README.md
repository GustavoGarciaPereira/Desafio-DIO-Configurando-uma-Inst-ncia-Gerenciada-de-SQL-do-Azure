# Desafio DIO: Configurando uma Instância Gerenciada de SQL do Azure

## Descrição do Projeto

Este repositório documenta o processo de configuração de uma Instância Gerenciada de SQL do Azure, como parte do desafio de projeto da Digital Innovation One. O objetivo é servir como um guia prático, consolidando os conhecimentos adquiridos sobre os serviços de banco de dados da Microsoft Azure e o uso do GitHub para documentação técnica.

## Objetivos de Aprendizagem

- Aplicar os conceitos de provisionamento e configuração de bancos de dados no Azure.
- Documentar processos técnicos de forma clara, estruturada e reproduzível.
- Utilizar o GitHub como ferramenta para versionamento e compartilhamento de documentação técnica.

## Tecnologias Utilizadas

- Microsoft Azure (Portal Azure, Instância Gerenciada de SQL)
- Git & GitHub
- Markdown

---

## Guia de Configuração da Instância Gerenciada de SQL do Azure

Esta seção detalha os passos seguidos para configurar a Instância Gerenciada de SQL no Azure.

### 1. Pré-requisitos

Antes de iniciar, certifique-se de que você possui:
- Uma assinatura ativa do Microsoft Azure.
- (Liste outros pré-requisitos que você identificou, como configuração de rede virtual, grupo de recursos, etc.)
- Conhecimento básico sobre redes virtuais (VNets) no Azure, pois a Instância Gerenciada requer uma.

### 2. Passo a Passo da Criação

Descreva aqui cada etapa do processo. Seja o mais detalhado possível.

#### 2.1. Acesso ao Portal Azure e Criação do Recurso
   - Como navegar até a opção de criar uma Instância Gerenciada de SQL.
   - (Opcional: Inclua um screenshot aqui: `![Nome da Imagem](../images/nome_da_imagem.png)`)

#### 2.2. Configurações Básicas
   - Escolha da assinatura, grupo de recursos.
   - Nome da instância gerenciada.
   - Região.
   - (Detalhe as escolhas que você fez e por quê, se relevante).

#### 2.3. Rede (Networking)
   - Configuração da Rede Virtual (VNet) e da sub-rede.
     - *Dica: Explique a importância da VNet dedicada ou dos requisitos específicos da sub-rede para a Instância Gerenciada.*
   - Tipo de conexão (público, privado).

#### 2.4. Configurações de Segurança
   - Autenticação (SQL, Azure AD).
   - Administrador do servidor.
   - (Mencione quaisquer outras configurações de segurança relevantes que você explorou).

#### 2.5. Configurações Adicionais (Computação + Armazenamento, Backup, etc.)
   - Escolha do nível de serviço (Uso Geral, Comercialmente Crítico).
   - Configuração de vCores e armazenamento.
   - Política de backup.
   - Collation.
   - Fuso horário.
   - *Dica: Explique brevemente as implicações de algumas dessas escolhas.*

#### 2.6. Revisão e Criação
   - O processo de validação.
   - Tempo estimado para o provisionamento.
   - (Opcional: Screenshot da tela de revisão).

### 3. Conectando-se à Instância Gerenciada
   - Ferramentas que podem ser usadas (SSMS, Azure Data Studio).
   - Como obter a string de conexão.
   - Pontos importantes sobre a conectividade (ex: necessidade de estar na mesma VNet ou ter um endpoint público configurado e regras de NSG).

---

## Anotações e Dicas Pessoais

Nesta seção, compartilhe suas percepções, desafios encontrados e como os superou.

- **Desafios Encontrados:**
  - (Ex: Dificuldade em configurar a VNet, entender algum parâmetro específico, tempo de provisionamento, etc.)
- **Soluções e Aprendizados:**
  - (Como você resolveu os desafios, o que aprendeu no processo.)
- **Dicas Importantes:**
  - (Ex: "Sempre verifique os pré-requisitos de rede antes de iniciar.", "A documentação oficial foi crucial para entender X.")
- **Pontos de Atenção:**
  - (Ex: Custos associados, implicações de segurança de certas configurações.)

---

## Recursos Úteis

Liste aqui os links que foram úteis para você, incluindo os fornecidos no desafio e quaisquer outros que você tenha encontrado.

- **Documentações Oficiais:**
  - [Início Rápido: criar Instância Gerenciada de SQL do Azure - Microsoft Learning](URL_DO_ARTIGO_MICROSOFT)
- **Materiais Complementares sobre GitHub:**
  - [GitHub Quick Start](URL_GITHUB_QUICK_START)
  - [GitBook: Formação GitHub Certification](URL_GITBOOK)
  - [Documentação do GitHub](URL_DOC_GITHUB)
  - [GitHub Markdown](URL_MARKDOWN_GITHUB)
- **Outros Recursos:**
  - (Adicione aqui links para vídeos, blogs, ou outras documentações que você consultou).

---

## Conclusão

Breve resumo do que foi alcançado e a importância do aprendizado.
