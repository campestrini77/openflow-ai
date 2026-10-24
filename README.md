# OpenFlow AI

Projeto educacional aberto para explorar automação, inteligência artificial e fluxos de trabalho eficientes.

## O que é
Uma landing page responsiva com uma demonstração interativa que cria um roteiro inicial de automação usando regras locais no navegador. Esta versão **não chama uma API de IA** e não envia o texto digitado para um servidor.

## Como visualizar
Abra `index.html` em um navegador moderno.

## Publicar no GitHub Pages
1. Crie um repositório público chamado `openflow-ai`.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/(root)`, depois clique em **Save**.
6. Aguarde a publicação e abra o endereço indicado na tela do GitHub Pages. Normalmente será `https://SEU-USUARIO.github.io/openflow-ai/`.

## Segurança
- Não coloque senhas, tokens, chaves de API ou dados pessoais nos arquivos públicos.
- Se conectar um serviço de IA futuramente, não exponha a chave de API no JavaScript do navegador. Use um backend seguro e variáveis de ambiente.
- Use apenas dados fictícios para testes públicos.

## Próximas melhorias
- Adicionar exemplos de fluxos de automação.
- Criar testes automatizados.
- Integrar uma API de IA por meio de um backend seguro.
- Documentar limitações, decisões técnicas e contribuições.

## Licença
Este projeto está disponibilizado sob a licença MIT. Consulte `LICENSE`.
