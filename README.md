# Skill portátil: Criar Currículo Canadense

Este pacote contém as instruções do plugin **Criar Currículo Canadense | Canadá Sem Filtro** em formato de skill. Ele ajuda a criar ou adaptar um currículo para vagas no Canadá usando somente os fatos informados pela pessoa.

**Novo:** [Guia ilustrado de instalação em PDF](guia-instalacao-curriculo-canadense.pdf), com passos para Claude, Codex e ChatGPT. No ChatGPT sem menu Skills, o guia mostra como usar o arquivo de instruções em um Projeto.

## Usar no Claude

1. Baixe [`criar-curriculo-canadense.zip`](criar-curriculo-canadense.zip).
2. No Claude, abra **Plugins** (ou **Customize > Skills**, se a interface ainda mostrar esse nome), clique em **+** e procure **Create skill > Upload a skill** ou a opção equivalente de importar uma skill.
3. Envie o arquivo ZIP e ative a skill.
4. Inicie uma conversa com: “Quero criar meu currículo canadense do zero” ou “Adapte meu currículo a esta vaga”.

O Claude exige que a opção de execução e criação de arquivos esteja habilitada para usar skills. Cada pessoa instala a skill na própria conta; o link do ZIP, por si só, não instala nem concede acesso a uma conta.

## Usar em outras ferramentas

O arquivo [`criar-curriculo-canadense/SKILL.md`](criar-curriculo-canadense/SKILL.md) usa o formato aberto Agent Skills. Ferramentas que aceitam esse formato podem carregar a pasta da skill. Em uma ferramenta sem suporte a skills, copie o conteúdo do arquivo para as instruções de um assistente personalizado.

Esta distribuição contém somente instruções. Ela não inclui dados de candidatos, conexões externas nem acesso ao aplicativo Rota do Emprego. O código do aplicativo fica em um repositório privado separado.
