# Classificador de Imagens Cães e Gatos

Este projeto consiste em um modelo de classificação de imagens que identifica se a imagem contém um cachorro ou um gato. O modelo é criado usando a biblioteca TensorFlow e é treinado no conjunto de dados CIFAR-10.

## Instalação

Antes de iniciar, é necessário instalar o TensorFlow e outras bibliotecas necessárias. Para fazer isso, execute o seguinte comando:


Em seguida, baixe o código-fonte do projeto do GitHub.

## Como usar

Para treinar o modelo, execute o seguinte comando:


Este comando treinará o modelo usando o conjunto de dados CIFAR-10 e salvará o modelo treinado em um arquivo chamado `model.h5`.

Para testar o modelo, execute o seguinte comando:


Este comando carregará o modelo treinado a partir do arquivo `model.h5` e usará-o para fazer previsões nas imagens do conjunto de dados de teste. Em seguida, as seguintes métricas serão calculadas:

- Acurácia
- Sensibilidade
- Precisão
- F1 Score
- Matriz de Confusão
- Curva ROC

Os resultados das métricas serão exibidos no console e a matriz de confusão e a curva ROC serão plotadas em gráficos.

## Contribuição

Contribuições são bem-vindas e encorajadas! Se você tiver ideias para melhorar este projeto, envie uma pull request ou crie uma nova issue.

## Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Se você tiver alguma dúvida ou quiser entrar em contato comigo, abra uma nova issue neste repositório.
