# Criptografia-Hash
Aplicação em Python para criptografia em hash

Introdução:

A função hash() do Python é uma função interna e retorna o valor hash de um objeto, se ele tiver um. O valor hash é um inteiro que é usado para comparar rapidamente chaves de dicionário enquanto olha para um dicionário.

Propriedades da função hash()
Objetos com hash usando hash() são irreversíveis, levando à perda de informações, hash() retorna valores hash somente para objetos imutáveis, portanto pode ser usado como um indicador para verificar objetos mutáveis/imutáveis.
Podemos codificar dados para segurança em Python usando a função hash().

Inciando o projeto:

Para iniciarmos o projeto, será necessário seguir os seguintes passos:

Clique em file -> New Project

![image](https://github.com/user-attachments/assets/6a46f478-769b-4946-b89b-886b0e5077cb)

Insira o nome do projeto.
Crie uma pasta do projeto
Marque para criar o repositorio no git

Interpreater Type: Project venv

![image](https://github.com/user-attachments/assets/b76cc064-d4d4-4612-ac57-f7978ed4cb98)

Após a criação do projeto, será necessário importar o hashlib

Tipos de criptografia:
MD5:
O algoritmo de hash MD5 usa uma fórmula matemática complexa para criar um hash . Ele converte dados em blocos de tamanhos específicos e manipula esses dados várias vezes. Enquanto isso acontece, o algoritmo adiciona um valor único ao cálculo e converte o resultado em uma pequena assinatura ou hash

SHA-1:
O hash SHA-1 é uma função criptográfica que converte uma string de qualquer tamanho em uma string de 40 caracteres. Essa string é uma representação textual do valor hexadecimal de uma soma de verificação de 160 bits. 

SHA-256:
SHA-256 é o algoritmo de hash seguro de 256 bits usado para proteção criptográfica. Os algoritmos de hash criptográficos produzem hashes irreversíveis e exclusivos. Quanto maior for o número de hashes, menor será a chance de dois valores criarem o mesmo hash.

SHA-512:
SHA-512 são funções hash inovadoras computadas com palavras de 64 bytes. Eles usam quantidades de deslocamento e constantes aditivas diferentes, mas as suas estruturas são praticamente idênticas, diferindo apenas no número de rodadas.

Segue o print do codigo:

![image](https://github.com/user-attachments/assets/f1113709-9f6b-4a27-9a45-8c0cafb65746)

Execução:

![image](https://github.com/user-attachments/assets/ccecb05e-5ee7-4495-8543-5948059d845a)

Para validar a criptografia, basta entrar no site abaixo e inserir a hash gerada:

#site para testar o tipo de codificação de senha: https://www.tunnelsup.com/hash-analyzer/

#site para validar senha: https://md5hashing.net/hash/md5
