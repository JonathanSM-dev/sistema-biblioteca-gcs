\# Política de Versionamento



\## Padrão: Semantic Versioning (SemVer)



\*\*Formato:\*\* MAJOR.MINOR.PATCH (X.Y.Z)



\- \*\*MAJOR:\*\* Mudanças incompatíveis com versões anteriores

\- \*\*MINOR:\*\* Novas funcionalidades mantendo compatibilidade

\- \*\*PATCH:\*\* Correções de bugs



\*\*Exemplo:\*\* v1.2.3

\- 1 = versão maior

\- 2 = funcionalidades adicionadas

\- 3 = correções aplicadas



---



\## Estratégia de Branches



\### Branches Principais

\- \*\*main\*\*: Código estável e testado

\- \*\*dev\*\*: Integração de funcionalidades



\### Branches de Suporte

\- \*\*feature/nome-funcionalidade\*\*: Desenvolvimento de novas features

\- \*\*fix/nome-bug\*\*: Correção de bugs



\### Regras

\- Nunca commitar direto na `main`

\- Merge em `main` apenas com código revisado

\- Deletar branches após merge



---



\## Padrão de Commits



\### Formato

```

tipo(escopo): descrição curta



\[corpo opcional com mais detalhes]

\[rodapé opcional com refs]

```



\### Tipos

\- \*\*feat\*\*: Nova funcionalidade

\- \*\*fix\*\*: Correção de bug

\- \*\*docs\*\*: Alteração em documentação

\- \*\*style\*\*: Formatação, ponto-vírgula (sem mudança de código)

\- \*\*refactor\*\*: Refatoração sem alterar funcionalidade

\- \*\*test\*\*: Adição ou correção de testes

\- \*\*chore\*\*: Tarefas de manutenção (build, configs)



\### Exemplos

```bash

feat(emprestimo): adiciona cálculo de multa por atraso

fix(usuario): corrige validação de email

docs(readme): atualiza instruções de instalação

```



---



\## Tags



\- Criar tag a cada versão estável

\- Formato: `vX.Y.Z`

\- Comando: `git tag -a v1.0.0 -m "Release inicial"`



---



\## Revisão



\- Todo código deve ser revisado antes do merge

\- Usar Pull Requests quando possível

\- Testar localmente antes de push

