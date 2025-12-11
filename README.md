# Curso Udemy - Aprenda Flutter e Desenvolva Apps

Este repositório serve como um portfólio de evolução, contendo todos os projetos práticos desenvolvidos durante o curso "Aprenda Flutter e Desenvolva Apps para Android e IOS".

## ⚠️ Sobre a Estrutura dos Arquivos

Para manter o repositório otimizado e focado no código que realmente importa, os projetos aqui listados contêm **apenas a pasta `lib`** (código-fonte principal) e arquivos de configuração essenciais quando necessário.

O objetivo é focar na lógica de negócio e construção de interface (UI/UX) aprendidas em cada módulo.

## 🚀 Como executar os projetos

Como os diretórios não contêm a infraestrutura completa do Android/iOS (pastas de build), siga este passo a passo para testar qualquer projeto deste repositório:

1. **Crie um novo projeto Flutter** no seu computador:
   ```bash
   flutter create nome_do_projeto
2. **Substitua a pasta lib:** Apague a pasta lib do projeto que você acabou de criar e cole a pasta lib do projeto deste repositório que deseja testar.
3. **Verifique as dependências (pubspec.yaml):**
   * Se houver um arquivo pubspec.yaml junto com a pasta do projeto aqui no GitHub, copie as dependências dele para o seu projeto.
   * Se não houver, o projeto utiliza apenas pacotes nativos do Flutter.
4. **Configurações Nativas (Android/iOS):** Caso o projeto exija configurações específicas (como permissões no AndroidManifest.xml ou Info.plist), haverá um aviso no README específico dentro da pasta do projeto.
5. **Execute o app:**
 ```bash
  flutter run
´´

**📂 Lista de Projetos**
#	Projeto	Descrição
01	Perguntas e Respostas	App de Quiz com lógica de pontuação e navegação.
02	Em breve...	...

------
Desenvolvido por Warlen.

### Para atualizar no GitHub:

Como você editou o arquivo, não esqueça de rodar os comandos para enviar a atualização:

```bash
git add README.md
git commit -m "docs: atualiza README com instruções de execução"
git pus
