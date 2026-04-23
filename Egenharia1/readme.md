### Software intangível

Os termos "engenharia de software" e "programação" tem sido utilizados como sinônimos, porém possuem ênfase e implicções diferentes. Assim como em outrs ramificações da engenharia os engenheiros de software também criam "algo real", embora sejam criaçõs menos tangíveis que as crições de outros engenheiros. Além disso, existe diferença na rigorosidade da teoria e prática atual da engenharia de software e das outras.

### Engenharia de Software = Programação + tempo, escalabilidade e trade-offs

A engenharia de software não deve ser apenas o ato de escrever código, mas todas as ferramentas e processos que uma organização utiliza para construir e manter o código ao longo do tempo. 
Existem 3 princípios fundamentais para as organzações de software terem em mente ao projetar, arquitetar e escrever um código, sendo eles, 1° Tempo e Mudaça, 2° Crescimento e 3° Trocas e Custos 
### Requisitos não fucionais 

* Escalabilidade - A escalabilidade é a qualidade que faz com que o software aguente grandes quantidades de requisições sem afetar a sua eficiência e rapidez, o sistema passa a ter autonomia para expandir ou retirar recursos conforme o número de demandas aumenta ou diminui. Agilidade - A agilidade de um software se refere a facilidade do sistema em se adaptar a mudanças, mantendo-o estável sem comprometer a sua velocidade, um software ágil possuí uma estrutura flexível, que permite redefinir as prioridades e corrigir erros sem desestabilizar o produto 	
* Segurança - A segurança se refere a como o software irá proteger os dados de seus usuários, softwares programados com esse requisito focam em proteção, confidencialidade e conformidade, um exemplo de software programado dessa formas são os aplicativos de bancos 
* Robustez - A robustez garante que o software irá conseguir lidar com situações imprevistas sem travar ou corromper dados, ele lida com o inesperado e anormal, como entradas inválidas. 
* Recuperabilidade - a recuperabilidade é a capacidade de um software se recuperar de falhas, erros ou interrupções, retornando rapidamente ao seu funcionamento normal e garantindo a integridade dos dados, focando sempre na velocidade e eficiência do sistema ao lidar com falhas. 
* Desempenho - O desempenho define como o software opera, focando em velocidade, eficiência e escalabilidade, e não nas funcionalidades em si, garantindo que o sistema responda rapidamente e suporte a carga de trabalho, influenciando diretamente a experiência do usuário

### Trade-offs (negociação entre requisitos não funcionais)

* Instagram (Agilidade) x Sistemas de controle de voo (Qualidade) - o Instagram foca na agilidade, assim eles buscam lançar códigos constantemente, porém não conseguem testar repetidamente esses códigos atrás de qualidade, assim podendo sofrer certos bugs.
* Softwares de dispositivos médicos (Robustez) x Sistemas de Intertravamento de Segurança (Confiabilidade) - dispositivos médicos precisam funcionar a todo momento, por isso eles precisam ceder um pouco de confiabilidade, pois ele 	continua operando em um nível básico para manter o paciente vivo, ignorando funções secundárias.
* ProtonMail (Segurança) x Gmail (Usabilidade) - por focar na segurança o ProtonMail perde um pouco da sua usabilidade, pois as mensagens são criptografadas de modo que ninguém possa lê-los, porém isso faz com que não consiga pesquisar os conteúdos das suas mensagens, além de que se você perder a senha de recuperação você perde todas as mensagens.
