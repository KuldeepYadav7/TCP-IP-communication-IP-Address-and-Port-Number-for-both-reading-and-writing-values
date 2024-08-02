# TCP-IP-communication-IP-Address-and-Port-Number-for-both-reading-and-writing-values

Overview
This project demonstrates a simple TCP/IP communication system using Boost.asio. The project includes a TCP server, a client application, and tests to verify the communication. The client connects to the server, sends a message, and reads the server's response. The tests ensure the communication is functioning correctly.

Project Structure
MyProject
│   CMakeLists.txt
│
└───src
    │   main.cpp
    │   test.cpp
    │   TCPIPCommunication.hpp
    │   TCPIPCommunication.cpp
    │   tcp_server.cpp
└───third_party
    │   catch.hpp

Setup Process
Prerequisites
1- Visual Studio Code: Download and install Visual Studio Code.
2- CMake: Download and install CMake.
3- Boost: Download and install Boost from Boost Libraries.

Build and Run the Project:

1- Open Visual Studio Code.
2- Open the Command Palette (Ctrl+Shift+P) and run CMake: Configure to configure the project.
3- Run CMake: Build to build the project, including the new tcp_server executable.

Run the Server:
1- Open a new terminal in Visual Studio Code.
2- Navigate to the build directory where the executables are located.
3- Run the TCP server:
cd C:\Users\HP\Downloads\MyProject\build\Debug
.\tcp_server.exe

Run the Client Application:
1 -Open another terminal in Visual Studio Code.
2- Navigate to the same directory where your executables are located.
3- Run the client application:
cd C:\Users\HP\Downloads\MyProject\build\Debug
.\manufacturing_plant.exe

Run the Tests:
1-Open another terminal in Visual Studio Code.
2-Navigate to the same directory where your executables are located.
3- Run the test application:
cd C:\Users\HP\Downloads\MyProject\build\Debug
.\test.exe




