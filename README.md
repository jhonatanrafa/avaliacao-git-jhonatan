# Despacha-te!

O **Despacha-te!** é uma app de gestão de tarefas simples e direta ao ponto. Serve para organizares o teu dia a dia, criares listas de afazeres e acompanhares o teu progresso em tempo real sem complicações. Cada tarefa tem prazo e prioridade, e o painel mostra sempre o que falta e o que já foi feito.

<p align="center">
  <img src="assets/despacha-te.png" width="420" alt="Logótipo Despacha-te!">
</p>

## Tecnologias utilizadas

| Nome       | Versão |                     Utilização |
|:-----------|:------:|-------------------------------:|
| HTML5      | 5.2    |         Estrutura das páginas  |
| CSS3       | 3.0    | Aparência e design responsivo  |
| JavaScript | ES2023 |      Interatividade da aplicação|
| MySQL      | 8.0    |      Base de dados das tarefas |

### Onde corre

A app corre no navegador, tanto no computador como no telemóvel. Para testar localmente usas o XAMPP, que traz o MySQL e o phpMyAdmin já instalados.

## Funcionalidades

- Criar, editar e eliminar tarefas
- Marcar uma tarefa como feita com um clique
- Filtrar por pendentes, concluídas ou todas
- Painel com o total de tarefas e o progresso

## Instalação

Para experimentar a app no teu computador:

1. Instala o XAMPP
2. Copia a pasta do projeto para `htdocs`
3. Importa o ficheiro `base_de_dados.sql` no phpMyAdmin
4. Altera os dados da base de dados no ficheiro `config.txt`
5. Abre `localhost` no navegador

### Configuração

No ficheiro `config.txt` ficam os dados de ligação à base de dados:

```
DATABASE_NAME = despachate
DATABASE_USERNAME = root
DATABASE_PASSWORD = 1234
```

## Tarefas por fazer

- [x] Lista de tarefas
- [x] Marcar tarefas como concluídas
- [ ] Exportar a lista para PDF
- [ ] Partilhar a lista por email

> Não deixes as tarefas acumular: despacha uma de cada vez.

## Autores

- Autor - Jhonatan Silva — [perfil no GitHub](https://github.com/jhonatanrafa)

---

*Desenvolvido no âmbito da atividade prática de Git & GitHub do curso Técnico de Desenvolvimento de Software (IEFP).*