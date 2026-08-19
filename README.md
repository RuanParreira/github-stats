# github-stats

Repositório de infraestrutura pessoal que gera as imagens de estatísticas (`overview.svg`, `languages.svg` e as respectivas versões dark) usadas no meu [README de perfil](https://github.com/RuanParreira/RuanParreira).

Uma GitHub Action roda periodicamente, coleta os dados via API do GitHub e commita os SVGs gerados na branch [`generated`](https://github.com/RuanParreira/github-stats/tree/generated) — sem depender de serviços públicos de terceiros que costumam ficar fora do ar.

Baseado no projeto [jstrieb/github-stats](https://github.com/jstrieb/github-stats), licenciado sob GPL-3.0.
