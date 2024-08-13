# ET256

## Tópicos:

1. — O que é Criptografia?
2. — Algoritmo AES e modo de operação CBC
3. — Instalação das ferramentas necessárias
   
   3.a — Anaconda
      * — Baixando e instalando o Anaconda
      * — O que são Ambientes Virtuais?
      * — Criando um Ambiente com o Anaconda
      * — Deletando um Ambiente Virtual
      * — Comandos úteis no Anaconda
   
   3.b — PyCryptodome
   
   3.c — Stdiomask
   
   3.d — Pyfiglet
   
4. — Criador
<br></br>
## 1. — O que é Criptografia?

> "**Criptografia é a prática de codificar e decodificar dados.** Quando os dados são criptografados, é aplicado um algoritmo para codificá-los de modo que eles não tenham mais o formato original e, portanto, não possam ser lidos. Os dados só podem ser decodificados ao formato original com o uso de uma chave de decriptografia específica." [[Fonte: Kaspersky]](https://www.kaspersky.com.br/resource-center/definitions/encryption)

## 2. — Algoritmo AES e modo de operação CBC

> **AES** significa *Advanced Encryption Standard* — é um padrão de **criptografia avançada**, estabelecida pelo *Instituto Nacional de Padrões e Tecnologia (NIST)* dos EUA em 2001.

> _**MODE_CBC**_ refere-se ao **modo de operação** em que a cifra trabalha com _**blocos de dados de tamanho fixo**_, podendo receber mensagens de *qualquer comprimento.*

## 3. — Instalação das ferramentas

### 3.a — Anaconda

> O **_Anaconda_** é uma poderosa solução tecnológica para a Ciência de Dados e pode abranger as linguagens _**Python**_ e _**R**_, contendo ferramentas potentes para a análise de dados. Mas aqui a usaremos para criar e gerenciar *Ambientes Virtuais* com praticidade.

### Baixando e instalando o Anaconda

Visite o [[Site de Download]](https://www.anaconda.com/products/individual#Downloads) e escolha o instalador que condiz com a sua máquina e sistema operacional e baixe-o. Também é relevante escolher a versão do Python que você quer que seja padrão (recomenda-se a 3.x).

Prossiga com a instalação clássica': *next, next, next..*, e lembre-se de deixar marcadas as opções que contém _**Recommended**_.

A escolha do local de instalação é opcional, mas é recomendado **não alterar a pasta de instalação**, porque está sujeito a conflitos.

Por fim, marque a opção _**Add Anaconda to my PATH environment variable**_ (mesmo que apareça _**not recommended**_ na descrição), porque só assim será possível usar o Anaconda no Prompt/Terminal, Git Bash, etc.

---

### O que são Ambientes Virtuais?

> Ambientes Virtuais são instalações isoladas do Python. Os Ambientes criados são tão úteis quanto as *branches* do Git — isto é — você pode isolar uma ou mais versões do Python com o Anaconda e fazer testes, sem interferir em um Ambiente Principal, também pode usar múltiplas versões do Python (2.7, 3.5, 3.6, 3.9...) conforme a necessidade.

### Criando um Ambiente com o Anaconda

A sintaxe é simples, algo como:

`conda create --name ENV_NAME python=x.x`

Sendo _**ENV_NAME**_ justamente o nome do seu ambiente e _**x.x**_ a versão do Python.

Exemplo:

`conda create --name py37 python=3.7`

Ao fazer o comando acima, será necessário confirmar algumas etapas no Prompt (ou Terminal). Mas também pode-se fazer direto usando essa sintaxe:

`conda create --name py37 python=3.7 -y`

( _-y_ irá dizer Yes/Sim em todas as etapas e criar o ambiente ).

***

### Deletando um Ambiente Virtual

`conda env remove --name ENV_NAME`

Sendo _**ENV_NAME**_ o nome usado no ambiente que você deseja deletar.

Exemplo:

`conda env remove --name py37`
<br></br>
### Comandos úteis no Anaconda

* Listar Ambientes Virtuais

    `conda env list`
    <br></br>

* No Conda v4.6+ (Windows, Linux e macOS)

    [Ativar o Ambiente]:
    
    `conda activate ENV_NAME`
    <br></br>
    [Desativar o Ambiente]:

    `conda deactivate`
    <br></br>

* Para versões anteriores ao conda 4.6, usar os seguintes comandos:

    Windows:
    `activate ENV_NAME` | `deactivate` (para ativar e desativar Ambientes, respectivamente).
    <br></br>

    Linux e macOS:

    `source activate ENV_NAME` | `source deactivate`
<br></br>
## 3.b — PyCryptodome
---

> "PyCryptodome é um pacote Python autossuficiente de primitivas criptográficas de baixo nível." [[Fonte: Introduction PyCryptodome]](https://www.pycryptodome.org/en/latest/src/introduction.html)


Instale o PyCryptodome facilmente:
    
- Ative o seu Ambiente Virtual no Terminal ou Prompt
- Faça o comando:

    `pip install pycryptodome`
<br></br>
## 3.c — Stdiomask
---

> "Um módulo Python multiplataforma para a entrada de senhas para um terminal de stdio e exibindo uma máscara ****..."

Instale o Stdiomask facilmente:

- Ative o seu Ambiente Virtual
- Faça o comando:

    `pip install stdiomask`
<br></br>
## 3.d — Pyfiglet
---

> "Pyfiglet é uma abertura completa do FIGlet (http://www.figlet.org/) para o Python puro. Ele pega o texto ASCII e o renderiza em fontes artísticas ASCII..."

*Exemplo:*
```
    _______________   ___________
   / ____/_  __/__ \ / ____/ ___/
  / __/   / /  __/ //___ \/ __ \ 
 / /___  / /  / __/____/ / /_/ / 
/_____/ /_/  /____/_____/\____/  
```
Instale o Pyfiglet facilmente:

- Ative o seu Ambiente Virtual
- Faça o comando:

    `pip install pyfiglet`
<br></br>

# 4. — Criador

![Image-logo-LinkedIn-48x48x](https://icons.iconarchive.com/icons/limav/flat-gradient-social/48/Linkedin-icon.png)

> #### [Carlos Aguiar](https://www.linkedin.com/in/aguiar0x01/)

---
