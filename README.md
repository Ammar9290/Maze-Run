use these commands to run it 
in ubuntu 

g++ maze.cpp -Idependencies/GLAD -Idependencies/STB -Ldependencies/GLAD -Ldependencies/STB ./dependencies/GLAD/libglad.a ./dependencies/STB/libstb.a -lglfw -lGL -lGLU -lX11 -lpthread -lXrandr -lXi -ldl -o maze

./maze


