# Programação orientada à objetos

Repositório de **Matheus Nascimento Adegas (582041 / 2º semestre)**
> ISSO NÃO É GPT! Estou só sendo técnico e tals! :P
</br>
25/09/2025 - Arquivo 25092025.ipynb, que contém as questões entregues em 24 de setembro.
</br>
> Inserção de coordenadas para pontos e comparação geométrica.
</br>
27/10/2025 - arquivo 27102025a.pynb, que contém questões de UML e classes em python.
> <img width="409" height="447" alt="image" src="https://github.com/user-attachments/assets/a6a87ea9-e124-4061-91b4-012ec9ebc0c6" />
</br>
29/10/2025 - novo arquivo zip com a atividade do dia 29.
</br> </br>
17/11/2025 - Entrega do sistema de gestão de campus proposta:
# Sistema de Gestão de Campus e Cursos – UFC

## 1. Objetivo do projeto

Este projeto implementa um sistema simples, em **Python**, para gerenciar:

- **Campus da UFC**
- **Cursos de cada campus**

O sistema é totalmente baseado em **listas** e em **Programação Orientada a Objetos (POO)**  
e permite realizar operações de **CRUD**:

- **C**reate → Cadastrar campus e cursos  
- **R**ead → Listar campus e cursos  
- **U**pdate → Atualizar dados de campus e cursos  
- **D**elete → Remover campus e cursos  

Tudo é feito por meio de um **menu interativo no terminal**.

---

## 2. Estrutura de arquivos do projeto
```text
projeto_ufc/
-> curso.py
-> campus.py
-> universidade.py
-> sistema.py
```

## 3. Execução do código
Para executar o código, basta escolher uma das 6 opções iniciais citadas no menu utilizando uma entrada com o numero especificado.
Para cadastrar um campus, digite 1, digite um numero ID do campus, o nome e a cidade.
Após isso, o campus estará armazenado e poderá ser mostrado ao selecionar 2 no menu principal, que é a opção de listar campus.
</br></br>
Após um campus ter sido criado, é possivel determinar os cursos dentro de cada campus com a opção 5 do menu principal, de gerenciar cursos. Após isso, especifique o campus com o ID que você determinou para um dos campus especificos. Após isso, será possivel cadastrar, listar, atualizar (modificar valores) e remover cursos dentro de um campus.
</br></br>
Para criar um curso, dentro de um campus, digite 1 para cadastrar curso. Após isso, escolha um ID para o curso. Então, escolha o nome e o tipo para concluir.
Após isso, o curso poderá ser visto dentro da opção 2: listar cursos, dentro de um campus.
