# bootcamp-gitflow

texto teste

# 🚀 Bootcamp de Engenharia de IA - Projeto Git Flow

Repositório de demonstração criado para aplicar e consolidar os conceitos de versionamento de código, fluxo de trabalho com Git Flow e padronização de commits.

---

## 🌳 Estrutura do Git Flow Utilizada

Este projeto segue o modelo **Git Flow** para garantir a organização e estabilidade do código entre os ambientes de desenvolvimento, validação e produção:

* **`main` / `production`**: Ambientes de produção. Contém o código estável que está em uso pelo usuário final.
* **`stage`**: Ambiente de homologação/validação (utilizado por QAs, POs ou clientes antes do deploy oficial).
* **`develop`**: Branch principal de desenvolvimento. É para onde todas as *features* e correções convergidas são enviadas inicialmente.
* **`feature/*`**: Branches criadas a partir da `develop` para desenvolver funcionalidades isoladas (ex: `feature/funcao-soma`).
* **`hotfix/*`**: Branches criadas a partir de `production` para correções urgentes em ambiente de produção.

---

## 📝 Padrão de Commits

Os commits deste repositório seguem convenções padronizadas para facilitar a leitura do histórico e identificar o propósito de cada alteração:

| Prefixo | Significado | Exemplo |
| :--- | :--- | :--- |
| `feat:` | Nova funcionalidade | `feat: adiciona função de soma no index.js` |
| `fix:` | Correção de bug / hotfix | `fix: altera regra de soma para multiplicação` |
| `docs:` | Mudanças na documentação | `docs: atualiza o README.md com guia do git` |
| `style:` | Formatação (espaços, ponto e vírgula) | `style: corrige indentação do arquivo` |
| `refactor:` | Refatoração sem mudar comportamento | `refactor: otimiza loop de cálculo` |

---