# Detector-de-EPIs

Este projeto tem como objetivo detectar Equipamentos de Proteção Individual (EPIs) em imagens utilizando modelos de visão computacional. Ele foi desenvolvido para auxiliar na análise de conformidade em ambientes industriais ou de trabalho.
O dataset utilizado no treinamento pode ser encontrado [aqui](https://www.kaggle.com/datasets/snehilsanyal/construction-site-safety-image-dataset-roboflow/data)

## Instruções para executar o código fonte

Você pode executar o código de duas maneiras: **localmente** ou pelo **Google Colab**.

### Executando no Google Colab

1. **Acesse o notebook no Google Colab**:  
   Clique [aqui](LINK) para acessar o notebook diretamente no Google Colab.

---

### Executando localmente

1. **Clone o repositório**:  
   No terminal, execute o comando:  
   ```bash
   git clone https://github.com/GusSampaio/Detector-de-EPIs.git
   cd Detector-de-EPIs
   ```

2. **Crie um ambiente virtual**:  
   Certifique-se de ter o Python 3.8+ instalado.  
   ```bash
   python -m venv venv
   source venv/bin/activate  # Para Linux/Mac
   venv\Scripts\activate     # Para Windows
   ```

3. **Instale as dependências**:  
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure os dados**:  
   - Baixe o conjunto de dados e salve-o no diretório `data/`.
   - Certifique-se de que os arquivos de configuração e pesos do modelo estejam no diretório `models/`.

5. **Execute o script principal**:  
   ```bash
   python main.py
   ```

---

## Estrutura do Projeto

- `data/`: Contém os arquivos de entrada e os conjuntos de dados.
- `models/`: Armazena os arquivos de configuração e pesos do modelo.
- `notebooks/`: Contém notebooks para execução no Google Colab.
- `src/`: Código-fonte do projeto.
  - `preprocessing/`: Scripts de pré-processamento dos dados.
  - `inference/`: Lógica para inferência com o modelo.
  - `evaluation/`: Scripts para avaliação do desempenho do modelo.
- `requirements.txt`: Dependências necessárias para o projeto.
- `main.py`: Ponto de entrada para executar a aplicação.

---

## Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature ou correção de bug:  
   ```bash
   git checkout -b minha-feature
   ```
3. Envie suas alterações:  
   ```bash
   git push origin minha-feature
   ```
4. Abra um Pull Request.

---

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

--- 

Se precisar de ajuda com mais informações ou ajustes, é só pedir! 😊
