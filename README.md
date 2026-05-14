# CP02_equipe2

Guilherme Cedro - RM: 571050

Matheus Pimenta Martini - RM: 569400

Gabiel Carvalho - RM: 571381

Leonardo Soares - M: 572986

---------------------------------------------------------

Prompt Engineering Toolkit — E-Commerce

Toolkit acadêmico de Prompt Engineering que aplica 4 técnicas de prompting sobre tarefas reais de atendimento ao cliente em e-commerce, compara resultados e gera relatórios automáticos.

-----------------------------------------------------------

O projeto recebe tarefas de negócio do domínio de e-commerce e aplica automaticamente as seguintes técnicas de prompting:

Zero-Shot: apenas instrução + input, sem exemplos

Few-Shot: instrução + exemplos reais antes do input

Chain of Thought: raciocínio passo a passo antes da resposta

Role Prompting: persona completa via system prompt

Os resultados são medidos em acurácia, tokens e tempo, e salvos em CSV com gráficos comparativos gerados automaticamente.

-------------------------------------------------------------

1. Clone ou baixe o projeto

cd Desktop
cd prompt-toolkit

2. Crie o ambiente virtual

python -m venv venv


3. Ative o ambiente virtual

venv\Scripts\activate

4. Instale as dependências

pip install -r requirements.txt

--------------------------------------------------------------

Ollama

1. Instale o Ollama

https://ollama.com/download

2. Baixe o modelo

ollama pull llama3.2

3. Verifique se o Ollama está rodando

ollama list

Como rodar

python main.py

---------------------------------------------------------------

Para executar:

python main.py



