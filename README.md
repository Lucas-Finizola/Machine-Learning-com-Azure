# Machine-Learning-com-Azure
Explorando a criação de uma machine learnig automática com o Azure

Para melhorar o entendimento do conteudo foi realizada uma ativdade para gerar uma machine learning autómatica no Azure IA.
Segue abaixo um breve passo a passo de como foi realizado.

Inicialmente foi realizada a esolha do nome do trabalho:
![Captura de tela_20250109_153558](https://github.com/user-attachments/assets/74371455-9074-4da7-a068-f2f819f8c52b)

logo após, foi a escolha do método de treinamento da máquina, que no caso seria a Regressão, cuja sua definição seria: 

"Os modelos de regressão são treinados para prever valores numéricos de rótulo com base em dados de treinamento que incluem recursos e rótulos conhecidos. O processo de treinamento de um modelo de regressão (ou qualquer modelo de machine learning supervisionado) envolve várias iterações nas quais você usa um algoritmo apropriado (geralmente com algumas configurações parametrizadas) para treinar um modelo, avaliar o desempenho preditivo do modelo e refinar o modelo repetindo o processo de treinamento com algoritmos e parâmetros diferentes até atingir um nível aceitável de precisão preditiva"

Em seguida, foi escolhido o banco de dados apresentado na própria documentação do Azure, um pequeno banco de dados sobre um historico de alugueis de bicicletas:
![Captura de tela_20250109_154510](https://github.com/user-attachments/assets/ff87690f-67f6-42db-939f-07478f8a59c6)

Depois de preencher todos os campos iniciais necessários, foi gerado pelo Azure uma ia com o metedo de treinamento escolhido, para realizar o trabalho:
![Captura de tela_20250109_155159](https://github.com/user-attachments/assets/0c733ad4-0cd6-42cc-9c37-b88559dc65d5)
![Captura de tela_20250109_171837](https://github.com/user-attachments/assets/1b149d7e-f3a6-417f-b75d-8179a8fdda55)

Também é possível ver todos os modelos escolhidos e qual foi que aprensentou a menor taxa de erro, inclusive a Métrica de avalição da regressão foi a REQM (Raiz do Erro Quadrático Médio): 
![Captura de tela_20250109_171847](https://github.com/user-attachments/assets/6039f3f3-2bdc-46c1-b129-ca401dfead7c)
E ao escolher o modelo que aprensentou menor taxa de erro, é possível visualizar diversas informações, como por exemplo uma representação gráfica dos resultados: 
![Captura de tela_20250109_162317](https://github.com/user-attachments/assets/899cee0e-47d9-4dbd-8519-d3bf550c5786)

Além de que na aba de "pontos de extremidade" é possível realizar vários teste especificos em tempos de sua preferencia, até mesmo em tempo real.





