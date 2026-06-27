# Política de Segurança

## Versões suportadas

Somente a versão mais recente da branch padrão de cada repositório ativo recebe correções de segurança, salvo indicação diferente no próprio projeto.

## Como reportar uma vulnerabilidade

Não abra uma issue pública para vulnerabilidades, credenciais expostas ou dados sensíveis.

Use o recurso **Report a vulnerability / Private vulnerability reporting** do repositório, quando disponível. Caso o recurso ainda não esteja habilitado, contate um Owner da organização por um canal privado previamente validado.

Inclua, quando possível:

- repositório e componente afetado;
- versão, commit ou ambiente;
- descrição do impacto;
- passos mínimos para reprodução;
- evidências sanitizadas, sem segredos reais;
- sugestão de mitigação, se conhecida.

## Tratamento

A equipe fará triagem, classificará severidade e impacto, definirá mitigação e registrará a correção por canal privado até que a divulgação seja segura.

## Regras obrigatórias

- Nunca publique tokens, senhas, chaves privadas, dados pessoais ou credenciais em issues, pull requests, commits, logs ou artefatos.
- Revogue imediatamente qualquer segredo potencialmente exposto; remover o texto do Git não torna o segredo seguro.
- Use secrets do GitHub Actions ou cofre aprovado, nunca arquivos versionados.
