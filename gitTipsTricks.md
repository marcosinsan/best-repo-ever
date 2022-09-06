## Como o Git armazena dados
    - Cada snapshot contém muitas informações. Cada um dos arquivos compactados no snapshot recebe um hash **SHA-1** exclusivo, conhecido como blobs. Esses blobs são referenciados por uma árvore e essa árvore é referenciada pelo commit.

## Explore seu histórico com o Git
    - Para acessar o histórico do seu projeto. Localmente, você pode usar **git log**.

    - O comando **git log** permite que você exiba uma lista de todos os commits em sua branch atual. Por padrão, o comando **git log** apresenta muitas informações de uma só vez.

    - Use alguns dos modificadores **git log** para cultivar uma lista de fácil leitura que forneça algumas informações valiosas.

        - **git log -10** : mostrará apenas os 10 commits mais recentes.
        - **git log --oneline** : é uma ótima maneira de visulizar o histórico de commits exibindo os primeiros sete caracteres do hash SHA-1 e a mensagem do commit dos commits na branch atual.
        - **git lolg --oneline --graph** : apresenta o histórico de commits em um gráfico ASCII exibindo os diferentes branches no repositórios e seus commits.
        - **git log --oneline --graph --decorate** : exibe o mesmo gráfico ASCII que é exibido usando o modificador *graph*, mas também inclui o(s) nome(s) das ramificações para os diferentes commits exibidos.
