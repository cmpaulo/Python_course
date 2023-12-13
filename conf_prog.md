**Configurando ambiente de programação**

Olá a todos!

Vamos embarcar em uma jornada de aprendizado e exploração no mundo da programação utilizando a linguagem Python. Python é conhecida por sua sintaxe simples, versatilidade e vasta comunidade de desenvolvedores, tornando-a uma escolha excelente para iniciantes e profissionais.

Para facilitar nosso caminho na programação em Python, estaremos utilizando o Jupyter Notebook, uma ferramenta que permite criar e compartilhar documentos interativos contendo código, visualizações e textos explicativos. Além disso, para tornar nossa experiência ainda mais acessível e colaborativa, vamos configurar o Google Colab, uma plataforma baseada na nuvem que nos permite executar notebooks Jupyter diretamente no navegador, sem a necessidade de instalações locais.

A configuração do Google Colab oferece vantagens como acesso a recursos computacionais poderosos, armazenamento na nuvem e a capacidade de colaborar em tempo real com colegas de equipe ou amigos.

O Google Colaboratory (ou Colab) é uma ferramenta poderosa para escrever e executar código Python diretamente no navegador. Ele oferece várias vantagens, como acesso a GPUs gratuitas, compartilhamento fácil e nenhuma configuração necessária. Vamos ver como começar a usá-lo:

**Utilizando o Google Colab.**

Voce vai precisar de uma conta Google se você não tem crie uma conta google e acesse o link [Google Colaboratory](https://colab.research.google.com/) https://colab.research.google.com/. Você será direcionado para um ambiente interativo chamado notebook Colab. Aqui estão algumas etapas para começar:

Células de Código: O Colab permite combinar código executável e texto em um só documento. Cada bloco de código é chamado de “célula”. Para executar uma célula, clique nela e pressione o botão “Play” à esquerda do código ou use o atalho do teclado Command/Ctrl+Enter.

Variáveis e Compartilhamento: As variáveis definidas em uma célula podem ser usadas em outras células. Os notebooks do Colab são armazenados na sua conta do Google Drive, e você pode compartilhá-los facilmente com colegas de trabalho ou amigos.

Ciência de Dados: O Colab é ótimo para análise de dados. Você pode importar dados do Google Drive, GitHub e outras fontes. Por exemplo, o código abaixo usa numpy e matplotlib para gerar dados aleatórios e visualizá-los:

Criar um Novo Notebook: Use o menu “Arquivo” acima ou clique em “Criar um novo notebook do Colab” para começar um novo projeto. Na primeira celula escreva o seguinte comando,

```
print("Olá, Mundo")
```

e após escrever o comando _print_ clique no sinal de _play_ ou _Ctr+Enter_, logo abaixo da célula irá parecer o texto *Olá, Mundo*

Lembre-se de que os notebooks do Colab são baseados no projeto Jupyter e são armazenados no seu Google Drive. Agora você está pronto para explorar e aproveitar todas as vantagens do Colab! 😊

## Guia de instalação do **Jupyter Notebook** no **Windows 10** e no **Linux Ubuntu**.

### Instalando o Jupyter Notebook no Windows 10:

1. **Abra o Prompt de Comando**:
   - Pressione a tecla **Windows + R** e digite `cmd` na caixa de diálogo Executar.
   - No prompt de comando, digite o seguinte comando para instalar o Jupyter Notebook:
     ```
     pip install jupyter
     ```

2. **Executando o Jupyter Notebook**:
   - Após a instalação, digite o seguinte comando para iniciar o Jupyter Notebook:
     ```
     jupyter notebook
     ```
   - Isso abrirá o Jupyter no seu navegador padrão, onde você pode criar e executar notebooks Python.

## Instalando o Jupyter Notebook no Linux Ubuntu:

1. **Atualize o Sistema**:
   - Abra o terminal e execute os seguintes comandos:
     ```
     sudo apt update
     sudo apt upgrade
     ```

2. **Instale o Python 3 e o pip**:
   - O Ubuntu 20.04 já vem com o Python 3 instalado. Para instalar o pip, execute:
     ```
     sudo apt install python3-pip
     ```
3. **Instale o Jupyter Notebook**:
   - Dentro do ambiente virtual, execute:
     ```
     pip install jupyter
     ```

4. **Execute o Jupyter Notebook**:
   - Digite o seguinte comando para iniciar o Jupyter:
     ```
     jupyter notebook
     ```
   - O Jupyter será aberto no seu navegador local.

Agora você está pronto para usar o Jupyter Notebook em ambos os sistemas! 🚀


(1) Project Jupyter | Installing Jupyter. https://jupyter.org/install.

Este é apenas o começo de uma jornada emocionante, e garantir que todos estejam preparados e configurados corretamente é crucial. Vamos começar instalando o Jupyter Notebook localmente e configurando o Google Colab para aproveitarmos ao máximo nossa experiência de programação em Python. Siga as instruções fornecidas para garantir que todos estejam prontos para mergulhar no incrível universo da programação com Python!

Vamos programar juntos!

**Referências:**

Project Jupyter | Installing Jupyter. https://jupyter.org/install.

[Voltar principal](readme.md)