Pesquisa: Fork e Formas de Organização do Trabalho com Filiais

**Autores:** Nome da(o) Aluna(o) = Evelin da silva barboza
**Turma:** 2º ano do Ensino Médio

1. O que é Fork

O termo fork significa “bifurcação”. No contexto do desenvolvimento de software e do GitHub, ele representa a criação de uma cópia independente de um repositório. Essa cópia permite que o usuário faça alterações sem interferir diretamente no projeto original.
O fork é muito utilizado em projetos colaborativos e de código aberto, onde desenvolvedores podem propor melhorias, correções ou adaptações próprias.
Após as modificações, o colaborador pode enviar um pull request para o repositório original, sugerindo a inclusão das mudanças.

2. Formas de Organização do Trabalho com Filiais (Branches)

O uso de filiais (branches) é essencial no controle de versões, pois permite que diferentes partes de um projeto sejam desenvolvidas simultaneamente sem afetar o código principal. Existem vários modelos de fluxo de trabalho, entre os quais se destacam GitHub Flow, Git Flow e Trunk-Based Development.

2.1 GitHub Flow

O GitHub Flow é um modelo simples e ágil, indicado para projetos que realizam atualizações contínuas. Ele é baseado em apenas uma branch principal (main) e em branches curtas criadas para novas funcionalidades.

Etapas do fluxo:

Criar uma nova branch a partir da main (exemplo: feature/nova-funcao);

Realizar as modificações e enviar os commits;

Abrir um Pull Request para revisão;

Após aprovação, realizar o merge na main.

Características principais:

Simplicidade e rapidez;

Integração contínua;

Ideal para projetos pequenos ou equipes que lançam atualizações com frequência.

2.2 Git Flow

O Git Flow é um modelo mais estruturado e completo, voltado para projetos de grande porte, que possuem ciclos de versão mais longos.
Ele organiza o trabalho com diversas branches, cada uma com uma função específica:

main: contém a versão estável do produto;

develop: branch de desenvolvimento principal;

feature/*: utilizada para novas funcionalidades;

release/*: preparação de novas versões;

hotfix/*: correções urgentes em produção.

Etapas do fluxo:

Criar uma branch feature a partir da develop;

Após finalizar a funcionalidade, realizar o merge na develop;

Criar uma branch release para testes e ajustes;

Unir a release à main e marcar a nova versão do software.

Características principais:

Organização rigorosa;

Facilita o controle de versões e correções;

Ideal para equipes grandes e projetos complexos.

2.3 Trunk-Based Development

O Trunk-Based Development é um modelo enxuto e disciplinado, que prioriza a integração constante. Nesse sistema, todos os desenvolvedores trabalham diretamente em uma única branch principal, chamada trunk ou main.

As alterações são pequenas e frequentes, e podem ser controladas por feature toggles (chaves de recurso), que permitem ativar ou desativar novas funcionalidades sem comprometer o código estável.

Etapas do fluxo:

Fazer pequenas alterações diretas na main;

Testar e integrar constantemente;

Utilizar automação e integração contínua (CI/CD).

Características principais:

Entregas rápidas e frequentes;

Menor risco de conflitos de código;

Exige disciplina da equipe e testes automatizados.

3. Comparação entre os Métodos
Método	Estrutura	Facilidade	Frequência de Deploy	Ideal Para
GitHub Flow	Simples (main + feature)	Alta	Alta	Projetos pequenos e ágeis
Git Flow	Complexa (várias branches)	Média	Moderada	Projetos grandes e organizados por versões

// Adiciona pesquisa sobre fork e fluxos de versionamento

Trunk-Based Development	Muito simples (main única)	Alta (com disciplina)	Muito alta	Equipes que usam integração contínua
4. Conclusão

Os diferentes modelos de organização de trabalho com branches refletem formas variadas de gerenciar o desenvolvimento de software.
O GitHub Flow prioriza a simplicidade e a agilidade; o Git Flow valoriza a organização e o controle de versões; enquanto o Trunk-Based Development foca na integração contínua e na entrega constante.
A escolha do método ideal depende do tamanho da equipe, da frequência de lançamentos e da complexidade do projeto.
