# Algoritmo de Reconhecimento de Atividade Humana

O software propõe uma estratégia baseada em sistemas inteligente para monitoramento de trabalhadores na realização de suas tarefas na indústria, visando prevenir doenças ocupacionais. Dados do sensoriamento de atividades rotineiras de um trabalhador são avaliados pelo software, que implementa reconhecimento de atividade humana, tendo como foco principal limitar o tempo máximo de execução de uma mesma atividade repetitiva.

## Segmentação dos dados
O software recebe como entrada um conjunto de dados gerados por acelerômetros triaxiais, que descrevem os movimentos realizados por um trabalhador em suas atividades. Para que seja possível o aprendizado do sistema inteligente de monitoramento, parte desses dados precisam estar devidamente rotuladas com a atividade respectiva que representam. A aquisição de dados não é parte integrante do software, sendo que os dados podem ser obtidos a partir de dispositivos como smartphones e smartwatches;

## Testes dos algoritmos
O software executa o processo de aprendizado de máquina a partir do conjunto de dados de atividades rotuladas, implementando as etapas de treino e teste;

Os classificadores de aprendizado de máquinas gerados podem então ser usados para classificar conjuntos de dados similares, a partir das atividades aprendidas;

O software permite controlar o número limite de repetições de uma atividade repetitiva, de modo a indicar quando é necessária uma pausa ou troca de atividade, com o objetivo de prevenir lesões e doenças laborais.
