#Titulo : Projeto Ros 

1. passo:
Criando um workspace(Pasta principal de trabalho) : 
 Codigo: 
  Mkdir -p /"Nome da pasta"_ws/src
  cd "Nome da pasta"_ws
  catkin_make
  
  
2. passo:
Criando um Package(Pacote fundamental do ros_ funções )
 Código 
 cd src 
 catkin_create_pkg <package_name> [depend1] [depend2] [depend3]
 EX:
  catkin_create_pkg "Nome do package"s std_msgs(dependências) rospy(dependências)
 
 No final execute: 
  source ./devel/setup.bash (Para que diabo ???)
 
3. passo: 
Crtiamos a pasta "script" dentro da pasta do package 
Por conseguinte colocamos os scripts(Publisher and subscribes) 

4. passo 
Execute 
rosrun "Package" "scripts"
    Tanto o publisher quanto o subscribe 
    
 
 
 
