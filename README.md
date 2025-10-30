[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=ff0000&size=35&center=true&vCenter=true&width=1000&lines=Atenção!+⚠;Não+nos+responsabilizamos+pelos+riscos)](https://git.io/typing-svg)

<h1 align="center">XPhisher</h1>

<p>Aviso importante: </p>
Este repositório contém material relacionado a técnicas de engenharia social e simulação de ataques. O conteúdo aqui publicado destina‑se exclusivamente a fins de pesquisa, educação e defesa. Não utilize nenhum dos artefatos, templates ou scripts contra terceiros sem autorização escrita e explícita. O proprietário do repositório e colaboradores não se responsabilizam por uso indevido.

------------------------------------------------------------------------

<h1 align="center">Visão geral</h1>

XPhisher é um conjunto de artefatos, exemplos e análises voltado para o estudo de ataques de engenharia social (phishing) com foco em prevenção, detecção e educação. O objetivo principal é permitir que profissionais de segurança, instrutores e pesquisadores avaliem riscos, criem simulações autorizadas e treinem usuários de forma segura.

Este repositório NÃO é um facilitador de crimes. Não contém instruções para coleta de credenciais reais nem orientações para executar ataques em ambientes de produção.

------------------------------------------------------------------------

<h1 align="center">Conteúdo do repositório</h1>

O repositório organiza o material em pastas lógicas. Resumo das áreas principais:

docs/ — documentação, referências e artigos explicativos sobre técnicas, mitigação e regulamentação.

examples/ — exemplos inertes (capturas de tela, HTML sem formulários ativos, snippets para análise estática) utilizados em treinamentos e apresentações.

research/ — análises, logs (sanitizados) e relatórios de campanhas simuladas realizadas com autorização.

tools/ — utilitários auxiliares seguros para gerar relatórios, produzir artefatos de teste (sempre inertes) e métricas. Não inclui ferramentas de ataque.

scripts/ — scripts de automação para ambiente de laboratório (apenas para criar ambientes isolados e limpar dados de teste).

------------------------------------------------------------------------

<h1 align="center">Uso responsável e recomendações</h1>

Antes de usar qualquer material deste repositório:

<p>Autorização: </p>
  obtenha autorização por escrito do proprietário do ambiente alvo (empresa, cliente, universidade). Documente escopo, duração e critérios de sucesso.

<p>Ambiente de teste: </p>
execute exemplos apenas em ambientes isolados (máquinas virtuais, redes laboratoriais) sem conexão a sistemas de produção.

<p>Não colete credenciais reais: </p>

configure landing pages educativas que NÃO solicitem ou armazenem senhas reais. Para medir comportamento, use contas de teste criadas especificamente para o exercício.

<p>Privacidade e conformidade: </p>

siga leis locais e políticas internas (LGPD, GDPR ou legislação aplicável). Obtenha aprovação do jurídico/compliance quando apropriado.

<p>Divulgação responsável: </p>

ao publicar relatórios ou amostras, sanitize dados sensíveis e remova qualquer informação identificável.

Instalação (ambiente de análise — apenas para fins educacionais)

Os passos abaixo descrevem como preparar um ambiente de análise seguro. Estes comandos não ativam, nem instruem a executar ataques.

Crie uma máquina virtual isolada (snapshot) com um sistema operacional de sua escolha.

Instale as dependências necessárias para análise (interpretes, ferramentas de inspeção, navegadores em modo teste).

Sempre revise o conteúdo dos arquivos antes de executar qualquer script: leia o código, cheque hashes e confirme a procedência.

Recomendamos fortemente o uso de snapshots e a restauração inicial após qualquer execução de laboratório.

------------------------------------------------------------------------

<h1 align="center">Boas práticas de contribuições</h1>

Contribuições são bem‑vindas desde que sigam princípios éticos e legais. Antes de abrir PRs ou issues, leia e cumpra estas regras:

Submeta apenas código e material que tenham finalidades defensivas, educativas ou de pesquisa. Evite incluir artefatos que possam ser usados de forma operacional para ataques.

Forneça descrição clara do propósito e da justificativa educacional/research para qualquer material sensível.

Inclua testes, documentação e exemplos que demonstrem o uso seguro do material.

Para dúvidas sobre aceitabilidade, abra uma issue descrevendo o caso antes de submeter código.

-------------------------------------------------------------------------------------

<h1 align="center">Política de segurança</h1>

Se você encontrar uma vulnerabilidade ou conteúdo sensível publicado inadvertidamente, por favor contate o mantenedor imediatamente e não publique detalhes públicos até que o problema seja resolvido. Use o canal de contato abaixo.

-------------------------------------------------------------------------------------

<h1 align="center">Licença</h1>

Este projeto é licenciado sob a GNU General Public License v3.0 (GPL‑3.0) — veja o arquivo LICENSE para o texto completo.

-------------------------------------------------------------------------------------

<h1 align="center">Contato</h1>

Mantenedor: Luthier2006
E‑mail: (adicione um e‑mail de contato aqui)
GitHub: https://github.com/Luthier2006

-------------------------------------------------------------------------------------

<h1 align="center">Agradecimentos</h1>

Referências e materiais de apoio: OWASP, literatura acadêmica sobre engenharia social, plataformas de awareness (GoPhish) e documentação de práticas seguras.
