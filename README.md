#  Projeto Ros 

## 1. Criando um workspace (Pasta principal de trabalho) 
    mkdir -p "Nome do Workspace_ws"/src
    cd "Nome do Workspace_ws"
    catkin_make
  
  
## 2. Criando um Package (Pacote fundamental do ros - funções )
    cd src 
    catkin_create_pkg <package_name> [depend1] [depend2] [depend3]
> Exemplo:

    catkin_create_pkg "Nome do package" std_msgs(dependência 1) rospy(dependência 2)
 
 **No final execute:**
    
    source ./devel/setup.bash
 
## 3. Criar a pasta "scripts" dentro da pasta do package 
Por conseguinte criar os scripts de Publisher e Subscriber 

## 4. Para executar os scripts
**Execute:**

    rosrun "package" "scripts"
> Tanto o publisher quanto o subscriber 
    
 
 
 
