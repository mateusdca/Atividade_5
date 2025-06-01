# Atividade_5
Atividade sobre manipulação de arquivos com java.

Reflexão Final:

O que acontece se você tentar ler um arquivo que não existe?

Se eu tentar ler um arquivo que não existe, o Java vai lançar uma exceção, geralmente do tipo FileNotFoundException. Isso acontece porque o programa não conseguiu localizar o arquivo no caminho que foi informado. Caso essa exceção não seja tratada com try-catch, o programa será interrompido e mostrará uma mensagem de erro. Por isso, é importante sempre tratar esse tipo de situação para evitar que o sistema pare de funcionar de forma inesperada.

Como poderíamos melhorar esse código usando try-with-resources?

Podemos melhorar o código usando try-with-resources, que é uma forma mais segura e prática de trabalhar com arquivos. Com essa estrutura, o próprio Java se encarrega de fechar os recursos usados, como FileReader ou BufferedReader, mesmo se acontecer algum erro durante a execução. Isso ajuda a evitar vazamentos de memória ou arquivos que ficam abertos sem necessidade, além de deixar o código mais organizado e fácil de manter.

Como salvar e ler arquivos com separadores diferentes, como JSON ou CSV?

Para salvar e ler arquivos com separadores diferentes, como JSON ou CSV, é preciso seguir o formato correto de cada tipo. No caso do CSV, os dados geralmente são separados por vírgulas, e podemos usar métodos como split(",") para separar as informações de cada linha. Já no formato JSON, os dados seguem uma estrutura com chaves e valores.
