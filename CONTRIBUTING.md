# Guia de Contribuição

## Fluxo padrão

1. Confirme o objetivo e o escopo da mudança.
2. Crie uma branch curta a partir da branch padrão atualizada.
3. Faça alterações pequenas, rastreáveis e sem dados sensíveis.
4. Execute as validações disponíveis no projeto.
5. Abra um pull request com contexto, riscos, testes e plano de reversão.
6. Aguarde os checks e a revisão antes do merge.

## Convenção de branches

- `feature/<descricao>` — nova funcionalidade;
- `fix/<descricao>` — correção;
- `docs/<descricao>` — documentação;
- `chore/<descricao>` — manutenção;
- `security/<descricao>` — correção de segurança;
- `governance/<descricao>` — políticas e governança.

## Commits

Prefira mensagens objetivas no padrão Conventional Commits:

- `feat:` funcionalidade;
- `fix:` correção;
- `docs:` documentação;
- `chore:` manutenção;
- `refactor:` refatoração;
- `test:` testes;
- `ci:` integração contínua.

## Critérios mínimos do pull request

- escopo declarado;
- issue ou demanda relacionada, quando houver;
- testes ou validação manual registrados;
- riscos e impacto identificados;
- ausência de segredos e dados pessoais;
- documentação atualizada quando necessária;
- reversão descrita para mudanças de risco médio ou alto.

## Segurança

Vulnerabilidades não devem ser reportadas em issues públicas. Consulte `SECURITY.md`.
