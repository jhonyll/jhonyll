# Meu site pessoal

Irei tentar descrever o que utilizei para construir o meu Site, tecnologias, estrutura de projeto, gambiarras e arte do GoHorse.

Nao sei qual a melhor parte para dar inicio a essa conversa, mas acrecredito que seja pelo comeco.

Pra ajudar antes que me esqueca, esse eh o link do meu site: [https://jhonatansilva.com/](https://jhonatansilva.com/)

## Estrutura do Projeto

A estrutura de diretorios que estou utilizando, herda um pouco da estrutura do `NextJS` framework principal do projeto e tbm dos meus desejos em deixar a coisa funcionando.

`.firebase`:

Esse eh um diretorio gerado pelo Firebase, onde estou hospedando a aplicacao, acredito que nem deveria estar sendo versionado, fato curioso que so percebi agora.

`.github`:

Diretorio que concentra algumas configuracoes do github, no meu caso apenas uma, a de workflows, uma especie de pipelines do github, que por sinal eh mamao com acucar, pois ter que utilizar outra ferramenta apartada para criar os arquivos `YAML` sem fim, para descrever como distribuir uma aplicacao confesso que eh um pouco chato.

`.vscode`:

Pasta do vscode onde existe um arquivo de `launch.json` para auxiliar no debug do site, sim da pra debuggar um site HTML.

`components`:

Agora vamos chegar nas regioes mais atrativas do projeto pra quem gosta de codigo, aqui esta localizado alguns components. Acredito que alguns components estao componentizados demais, pois percebi que tenho um `header.jsx`, `headerPage.jsx`, `template.jsx`, `documentHead.jsx` e um `menu.jsx`.

`data`:

Alguns objetos com as informacoes do site, tipo:

- `contact.js` minhas informacoes de contato
- `experience.js` uma lista ateh que grande de lugares q trabalhei
- `link` aqui estao os links do menu
- `project.js` informacoes utilizadas na pagina de `/lab`
