# Redes de Computadores

Anotações dos meus estudos sobre o livro Rede de Computadores do [Tanenbaum](https://archive.org/details/tanenbaum-rede-de-computadores-6a/page/n11/mode/2up).

# I. Introdução

## Usos de redes de computadores

O velho modelo de um único computador atendendo a todas as necessidades computacionais da organização foi substituído por outro em que os trabalhos são realizados por um grande número de computadores separados, porém interconectados. Esses sistemas são chamados de **redes de computadores**.

Grande parte das informações na Internet é acessada por meio de um modelo cliente-servidor, no qual um cliente solicita explicitamente informações de um servidor que as hospeda.

O **modelo cliente-servidor** é bastante usado e forma a base de grande parte do uso da rede. A realização mais popular é a de uma **aplicação Web**, em que o servidor fornece páginas Web com base em seu banco de dados em resposta às solicitações do cliente.

Outro modelo popular para acessar informações é a comunicação **peer-to-peer** (ou não hierárquica). Nessa forma de comunicação, indivíduos que constituem um grupo livre podem se comunicar com outros participantes do grupo. Em princípio, toda pessoa pode se comunicar com uma ou mais pessoas; não existe qualquer divisão estrita entre clientes e servidores.

Muitos sistemas peer-to-peer não possuem qualquer banco de dados de conteúdo central. Em vez disso, cada usuário mantém seu próprio abnco de dados no local e oferece uma lista de outros membros do sistema.

Essa revolução contínua, normalmente chamada de **IoT** (**Internet das Coisas**), está preparada para conectar à Internet praticamente qualquer dispositivo eletrônico que compramos.

## Tipos de redes de computadores

Existem muitos tipos distintos de redes de computadores.

O acesso à Internet oferece, aos usuários domésticos, **conectividade** a computadores remotos. Assim como as empresas, os usuários domésticos podem acessar informações, comunicar-se com outras pessoas e comprar produtos e serviços com o comércio eletrônico. O principal benefício agora vem da conexão com o exterior da casa. Bob Metcalfe, o inventor da Ethernet, formulou a hipótese de que o valor de uma rede é proporcional ao quadrado do número de usuários, pois esse é aproximadamente o número de conexões diferentes que podem ser feitas. Essa hipótese é conhecida como a "Lei de Metcalfe". Ela ajuda a explicar como a tremenda popularidade da Internet vem de seu tamanho.

As redes sem fio também são importantes para os militares. Se, de uma horapara outra, for necessário travar uma guerra em qualquer lugar no mundo, talvez não seja possível contar com a possibilidade de usar a infraestrutura de uma rede local. Será melhor levar seu próprio equipamento de rede.

Existe uma distinção entre redes sem **fio fixas** e **sem fio** móveis. Um exemplo é um notebook que é móvel, mas não sem fio. Já redes em edifícios que não dispõem de fiação não são móveis. Agora, um computador portátil que registra o estoque de uma loja é sem fio e móvel.

Muitos serviços da Internet agora são atendidos "pela nuvem" ou em uma **rede de centro de dados** (ou "data center"). As redes de centro de dados atendem às crescentes demandas da **computação em nuvem** e são projetadas para mover grandes quantidades de dados entre os servidores no centro de dados, bem como entre o centro de dados e o restante da Internet.

Um dos principais desafios de throughput da rede é a chamada "largura de banda da seção transversal", que é a taxa de dados que pode ser entregue entre dois servidores.

>Os primeiros projetos de rede de centro de dados eram baseados em uma topologia simples em árvore, com três camadas de switches: acesso, agregação e núcleo; este esquema simples não podia ser expandido com facilidade e também era sujeito a falhas.

Muitos serviços populares da Internet precisam oferecer conteúdo a usuários em todo o mundo. Para isso, muitos sites e serviços na Internet utilizam uma **CDN (Content Delivery Network)**, que é um grande conjunto de servidores distribuídos geograficamente, de modo que o conteúdo é colocado o mais próximo possível dos usuários que o estão solicitando.

O **compartilhamento de recursos** torna programas, equipamentos e especialmente dados ao alcance de todas as pessoas na rede, independentemente da localização física do recurso ou do usuário. Um exemplo óbvio e bastante disseminado é um grupo de funcionários de um escritório que compartilham uma impressora comum.

Redes chamadas **VPNs (Virtual Private Networks)** podem ser usadas para unir as redes individuais em diferentes locais em uma rede lógica. Resumindo, trata-se de uma tentativa de dar fim à "tirania da geografia".

## Tecnologia de redes locais a globais

As **redes pessoais**, ou **PANs (Personal Area Networks)**, permitem que dispositivos se comuniquem pelo alcance de uma pessoa.

Uma rede local, **LAN (Local Area Network)** é uma rede particular que opera dentro e próximo de um único prédio, como uma residência, um escritório ou uma fábrica.

As LANs sem fio são muito populares atualmente. Quase sempre, cada computador fala com um dispositivo chamado **ponto de acesso (AP - Access Point)**, **roteador sem fio** ou **estação-base**. Esse dispositivo repassa os pacotes entre os computadores sem fio e também entre eles e a Internet. Ser o AP é como ser o garoto popular na escola, pois todos querem falar com você.

Existe um padrão para as LANs sem fio, chamado **IEEE 802.11**, popularmente conhecido como WiFi. Ele trabalha em velocidades de 11 Mbps (802.11b) a 7 Gbps (802.11ad).

Normalmente, as LANs com fio trabalham em velocidades de 100 Mbps a 40 Gpbs, têm baixo atraso de transporte de dados e com elas ocorrem poucos erros de transmissão. Têm menor latência, menor perda de pacotes e maior throughput que as LANs sem fio. O **IEEE 802.3**, popularmente chamado **Ethernet**, é o tipo mais comum de LAN com fio.

## Exemplos de redes

## Protocolos de rede

## Modelos de referência

## Padronização de redes

## Questões políticas, legais e sociais

## Unidades de medida

## Resumo