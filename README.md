# Roteiro de Estudos

## Informações e metodologia

### Requisitos de Hardware e Software utilizados
* Hardware
     * Processador 8ª ger. Intel Core i5
     * 8GB RAM / 1TB HD
* Software
     * 20.04.5 LTS (Focal Fossa)

### Sobre o Jupyter
* O Jupyter é uma ferramenta _web open source_ que permite editar e compilar trechos de código de diversas linguagens de programação, entre elas o Python. É uma alternativa muito interessante para quem está aprendendo uma nova tecnologia e pode ser instalado na máquina por meio do Anaconda ou com `pip install jupyter` (ou de forma análoga, `pip3 install jupyter`). Após instalar a ferramenta e tentar executá-la (no sistema operacional Linux) o terminal pode retornar a seguinte mensagem
`Command 'jupyter-notebook' not found, but can be installed with: sudo apt install jupyter-notebook`

     Isso ocorre pois o pip instala os executáveis do Jupyter no diretório *.local*, então se faz necessário confirmar que **.local/bin/** está adicionado à PATH, o que pode ser feito com `export PATH=$PATH:~/.local/bin` (de forma temporária a cada execução) ou editando **~/.bashrc** para garantir as mudanças para ocasiões futuras. Em seguida, o Jupyter pode ser executado com `jupyter notebook`. Disponível em: <[https://stackoverflow.com/questions/35313876/after-installing-with-pip-jupyter-command-not-found](https://stackoverflow.com/questions/35313876/after-installing-with-pip-jupyter-command-not-found)>.

* **Instalação feita no Ubuntu 20.04LTS**
     * `sudo apt-get install python3-pip python3-dev` (Por padrão, o Python 3 já vem nessa versão do Ubuntu)
     * `sudo su`
     * `pip3 install jupyter`
     * `exit`
     * `jupyter notebook` (Comando para executar o Jupyter)



## Links Úteis & Referências
1. Jupyter Notebook. Disponível em <[https://jupyter.org/](https://jupyter.org/)>. Acesso em: 2 de Abril de 2022.
2. JupyterLite Retro. Disponível em: <[https://jupyter.org/try-jupyter/retro/notebooks/?path=Untitled.ipynb](https://jupyter.org/try-jupyter/retro/notebooks/?path=Untitled.ipynb)>
3. Try Jupyter. Disponível em: <[https://docs.jupyter.org/en/latest/start/index.html](https://docs.jupyter.org/en/latest/start/index.html)>
4. Try Jupyter - Use our tools without installing anything. Disponível em: <[https://jupyter.org/try](https://jupyter.org/try)>
5. Installing Jupyter - Get up and running on your computer. Disponível em: <[https://jupyter.org/install](https://jupyter.org/install)>
