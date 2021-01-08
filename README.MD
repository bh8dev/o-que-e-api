# O que é uma API?

API (Application Program Interface) é um conjunto de definições e protocolos usado no desenvolvimento e na integração de software e de aplicações. API é um acrônimo em inglês que significa interface de programação de aplicações.

## Para que serve?

Basicamente uma API é uma interface (contrato) entre aplicativo e programação.
Ela é a interface ideal para que um sistema se comunique com outro sistema.

> Ex: Uma interface de um sistema é criada para ser usada por um usuário final. A API é desenvolvida para que um sistema possa usar as funcionalidades de um outro sistema, programaticamente.

## Aplicabilidade na vida real

Um sistema de controle de Ordem de Serviço (OS), neste exemplo um serviço que os profissionais necessitam ficar transitando pela cidade, esse sistema controla essas ordens de serviço.
Vamos supor que há uma manutenção em uma rede elétrica ou cerca elétrica hoje a tarde.
O sistema vai consultar um serviço de meteorologia e ver se há possibilidade de chuva hoje a tarde.
Se houver chance de chuva o sistema envia algum tipo de aviso ao profissional, podendo ser para ter cuidado, para remarcar, etc... algum tipo de aviso.

Uma empresa X que presta serviços de meteorologia, ela irá ter uma API, e esse sistema de OS irá consumir(fazer uma requisição) à esse sistema de dados meteorológicos para saber qual a condição climática, etc... e obter essas informações.
A API não necessita de nada visual para consulta dos dados, o sistema de OS simplesmente passa por exemplo: na data X, na localidade Y, no horário Z, como estará o clima? probabilidade de chuva? etc..

## Referências

### RedHat

**Em texto**:
[RedHat](https://www.redhat.com/pt-br/topics/api/what-are-application-programming-interfaces)

### Código Fonte TV

**Em vídeo**:
[CDFTV](https://youtu.be/vGuqKIRWosk)

## Na prática

> Tipos de Métodos

- GET;
- POST;
- PUT;
- DELETE;
- OPTIONS;
- HEAD;

## Retornos

- JSON
- XML
- Texto puro

## Exemplos

**Retorno em JSON:**
[B7Web](https://api.b7web.com.br/ping/)

**Retorno em XML:**
[Correios](http://webservice.correios.com.br/service/rastro/Rastro.wsdl)

**Retorno em Texto**:
[B7Web](https://api.b7web.com.br)
