# Content: Reinforcement Learning 
## Nanodegree Machine Learning Engineer - Udacity
## Project: Train a Quadcopter How to Fly

Reinforcement learning material, code and exercises for [Udacity](https://www.udacity.com/) Nanodegree programs.

* Ensine um quadcopter a voar! *

Neste projeto, você projetará um agente para pilotar um quadcopter e o treinará usando um algoritmo de aprendizado por reforço de sua escolha! 

##  Instruções do projeto

1. Clone o repositório e navegue até a pasta baixada.

`` ``
git clone https://github.com/udacity/RL-Quadcopter-2.git
cd RL-Quadcopter-2
`` ``

2. Crie e ative um novo ambiente.

`` ``
conda create -n quadcop python = 3.6 matplotlib numpy pandas
fonte ativar quadcop
`` ``

3. Crie um [ kernel do IPython ] (http://ipython.readthedocs.io/en/stable/install/kernel_install.html) para o ambiente do `quadcop` .
`` ``
python -m instalação do ipykernel --user --name quadcop --display-name "quadcop"
`` ``

4. Abra o notebook.
`` ``
notebook jupyter Quadcopter_Project.ipynb
`` ``

5. Antes de executar o código, altere o kernel para corresponder ao ambiente `quadcop` usando o menu suspenso ( ** Kernel> Alterar kernel> quadcop ** ). Em seguida, siga as instruções no caderno.

6. Você provavelmente precisará instalar mais pacotes de pip para concluir este projeto:
matplotlib == 2.0.0
numpy == 1.14.1
pandas == 0.19.2 