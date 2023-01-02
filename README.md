
# What is this? 
A C++ implementation of an **artificial intelligence** that can drive at unbelievable speed on *any* given circuit!

<p align="center">
  <img src="https://github.com/fabriziotappero/Learn_To_Drive_CPP/blob/main/assets/hero.png?raw=true" width = "100%" alt="" align=center/>
</p>

# How to compile
Install g++ (in Windows you can use MSYS2) and run:

    g++ -o main.exe main.cpp -O2 -s -DNDEBUG -luser32 -lgdi32 -lopengl32 -lgdiplus -lShlwapi -ldwmapi -lstdc++fs -static -std=c++17

 # What it does
You give it a race circuit (as an PNG image) and you let the car run how to drive. After a cetain amount of iteration the car will be able to drive al maximum speed around the circuit!
 
 As you might have noticed from the code, it uses the great open-source **Pixel Game Engine** by olc. Have a look here for into and documentation:
 
 https://github.com/OneLoneCoder/olcPixelGameEngine
 
 # Why I made this
 Essentially I wanted to improve my C++ skills by implementing an *articial intelligence* that can process images in real time using a *graphic game engine*. 
 If you actually want to implement stuff it is a good idea to find data to process, a game engine has indeed a ton of video data!
 
 Regarding AI, on the web you can find a lot of implementations made in Python but not so many made in C++.
 
 # Reach out
 If you want to know more:
 
     fabrizio.tappero@gmail.com
