## aws-stepfunctions-examples

AWS Step Functions é um serviço que  fornece orquestração sem servidor para aplicações modernas.

O Step Functions é um serviço de fluxo de trabalho visual que ajuda os desenvolvedores a usar os produtos da AWS para desenvolver aplicações distribuídas, automatizar processos, orquestrar microsserviços e criar pipelines de dados e machine learning (ML).


A Aws oferece modelos de fluxo pré pronto  e completamente editável,podendo ser excluiído ou aalterado
Também pode ser criado um fluxo do início.
Workflow Studio ajuda no aprendizado, ao efetuar projetos de fluxo e codificaçao de trabalho utilizando template básicos.

É um serviço Low code, tem a opçao de usar gráfico ou código e efetuar configurações e com Layout bem intuitivo.

As definições de estado de máquina são escrita em ASL(Amazon State Language) baseado na linguagem JSON.

A  cobrança do Step Functios  a cobrança é feita por execução do Serviço, a orientação é semppre verificar o valor do serviço a ser utilizado.
Exemplo, Na aula dada foi utilizado o Badrock e EC2, será cobrado as execuçoes de cada serviço.

Configurações.
No estado de máquina tem as configurações de perfil de usuário do serviço, é  nessário eentrar no console do IAM e dar as permissões necessárias.

E após  permissões no  perfil do  usuario de serviço , clicar em estado de Máquina e permiçoes no inspetor e dar permisão no modelo de serviço desejado e se certificar se esta disponivel na conta uma determinada região.

Nas confirgurações de inspetor no Step Functions sempre verificar o usuário tem acesso ao modelo selecionado.
Caso não tenha, será necessário configurar o acesso ao modelo ou versão na rgiaão que você tem a conta da AWS

e último configurar os parametros das configurações do modelo selecionado.

Fontes: https://aws.amazon.com/pt/step-functions/




