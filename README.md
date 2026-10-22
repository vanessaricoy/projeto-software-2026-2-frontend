
# gameLibrary 2.0

Frontend do projeto de software 2026.2.

Aplicação para organizar uma biblioteca de jogos, gerenciar coleções e cadastrar trilhas sonoras.

## Tecnologias

- HTML5
- CSS3
- JavaScript
- API REST
- RAWG API (integração pelo backend)

## Funcionalidades

- Biblioteca de jogos
- Dashboard com estatísticas
- Jogos em destaque
- Pesquisa e filtros
- Coleções: Favoritos, Lista de compras e Quero jogar
- Cadastro, edição e exclusão de jogos
- Busca no catálogo RAWG
- Detalhes de jogos
- Gerenciamento de trilhas sonoras
- Layout responsivo
- Modo demonstração sem backend

## Como executar

Na pasta do projeto:

```bash
python3 -m http.server 5500
```

Acesse:

http://localhost:5500/?demo=1#/

## Modo demonstração

O modo demonstração permite navegar pelo frontend sem iniciar o backend.

Inclui 12 jogos e trilhas de exemplo.

As alterações feitas nesse modo são temporárias e desaparecem ao atualizar a página.

## Integração com o backend

Endpoints previstos:

- Jogos: http://localhost:8080/api/jogos
- Músicas: http://localhost:8082/api/musicas
- Enlistamentos: http://localhost:8083/api/enlistamentos

Para usar os serviços reais, acesse:

http://localhost:5500/?demo=0#/

O backend deve estar em execução e permitir requisições do frontend via CORS.

## Observações

A integração completa com os microsserviços deve ser validada pela equipe.

As capas de demonstração são ilustrações abstratas. Quando disponíveis, as imagens do catálogo RAWG podem substituí-las.
