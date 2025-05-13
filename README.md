# Teste de front-end

Este projeto foi criado usando o [Ktor Project Generator](https://ktor.io/).

Aqui estão alguns links úteis para você começar:

- [Documentação do Ktor](https://ktor.io/docs/)
- [Página do Ktor no GitHub](https://github.com/ktorio/ktor)
- O bate-papo do [Ktor Slack](https://slack.ktor.io/). Você precisará de: para [solicitar um convite](https://slack.ktor.io/) para participar.

## Características

Aqui está uma lista de recursos incluídos neste projeto:

| Nome       | Descrição                                                  |
|------------|------------------------------------------------------------|
| Roteamento | Permite definir rotas estruturadas e manipuladores associados |

## Construindo & Executando

Para criar ou executar o projeto, use uma das seguintes tarefas:

| Tarefa                                | Descrição                                                  |
|----------------------------------------|------------------------------------------------------------|
| `./gradlew test`                       | Execute os testes                                          |
| `./gradlew build`                      | Construa tudo                                              |
| `buildFatJar`                          | Crie um JAR executável do servidor com todas as dependências incluídas |
| `buildImage`                           | Crie a imagem do docker para usar com o JAR gordo          |
| `publishImageToLocalRegistry`          | Publicar a imagem do docker localmente                     |
| `run`                                  | Execute o servidor                                         |
| `runDocker`                            | Executar usando a imagem do docker local                   |

Se o servidor for iniciado com êxito, você verá a seguinte saída:

