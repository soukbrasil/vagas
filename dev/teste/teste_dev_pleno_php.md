## Problema X 

Precisamos que dois serviços se comuniquem entre si, em rede privada, onde o primeiro lê um arquivo em CSV com uma lista de clientes e deve enviar estes dados normalizados para que o segundo serviço processe estas informações e salve os dados no banco.

Premissas:
> - Um cliente não pode ter mais de um cadastro. Ou seja, caso já exista, seu cadastro deve ser atualizado e não duplicado. CNPJ é a chave única.
>
> - O arquivo CSV pode ter entre 1000 e 1000000 de linhas, performance é um requisito.
>
> - A implementação deve ser feita utilizando Laravel em ambos os serviços.
>
> - Não se preocupar com autenticação

Não existe uma única resposta correta, o que queremos avaliar é a abordagem tomada pelo candidato.

O teste pode ser respondido com uma implementação exemplificando a solução ou com uma sugestão detalhada de arquitetura para este problema.

A ideia é avaliar a linha de raciocínio lógico e cuidado com detalhes, muito mais do que o código de fato produzido.

Hospede seu teste em um repositório público do Github/Gitlab/Bitbucker sem mencionar que é para a vaga que a Souk está disponibilizando, e nos informe a url do projeto.

Boa Sorte!

PS.: Pode ficar tranquilo que já temos esta funcionalidade implementada hoje, não estamos falando para você criar isso para usar depois. (É cruel mas é real tem empresas que faz isto com os candidatos 🙁).