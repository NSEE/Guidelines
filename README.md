# Guidelines
Recomendações e ferramentas para criação e manutenção de projetos.
Esse repositório servirá como exemplo para a organização e padronização do software gerado no NSEE. 

## 1# Elicitação de Requisitos
Preferência pelo uso do Github Projects para listar e organizar requisitos e seu estado atual de desenvolvimento.
  
## 2# Model Based Design (MBD)*
Recomenda-se, quando aplicável, o uso do MBD para gerar software a partir de um modelo;
Criação de modelos não só permitem automação na criação de estruturas de código como também de sua documentação.

As seguintes ferramentas open source podem ser exploradas:
- Modelio
- PlantUML

## 3# Testes e Integração
A execução de testes é imprescindível para tornar o código confiável.
Dentre a infinidade de testes existentes, podemos ressaltar os seguintes devido à sua importância:
- Regressão
- Integração
- Unidade

## 4# Rotina de Desenvolvimento
O uso dos Issues pode ser explorado pela equipe para requisição de novas funcionalidades, correção de bugs e até discussões técnicas.

## 5# Depolyment, Automação e Documentação
Destaca-se nesse repositório a existência de arquivos .yaml de exemplo para execução de tarefas pelo Github Actions;

Ao enviar código para o repositório, a execução do script é chamada, podendo ser executada em um ambiente cedido pelo Github ou um self-hosted runner.
No NSEE a preferência deverá ser do uso de self-hosted runners. Porém, vale lembrar que os repositórios não devem aceitar Pull Requests de fora
da equipe de trabalho (Isso pode abrir espaço para a execução de código malicioso em nossos servidores).

A documentação poderá ser feita com o Sphinx e hospedada no servidor do NSEE ou simplesmente enviada para o sub-repositório Wiki que o Github provê (isso tudo poderá ser automatizado também).
A preferência é pelo uso de Markdown (MD) devido à sua simplicidade e clareza.

## #6 Versionamento
Seguir o padrão X.Y.Z ao menos para a criação de pacotes para produção.
- Major.Minor.Fixes
- Release.Beta.Alpha

## #7 Boas Práticas
- Tente fazer ao menos um commit por dia de trabalho.
- Evite trabalhar no Master. Prefira trabalhar em branches e depois fazer o Merge através de Pull Requests.
- Descreva seus commits e procure seguir um padrão.



*[Não obrigatório]


