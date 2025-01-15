# artistryConnect
Artistry Connect:

Intro:

Artistry Connect is a platform designed to
Empower Artists.
Providing them with a Digital Space To Showcase and Manage their Creative Portfolios.



Language Used:

C++


IDE Used:

QT Creator 15.0.0 (community)


User Interface:
We used QWigdet for the UI in QT Creator. 
![image](https://github.com/user-attachments/assets/8f35f150-bd91-44e7-83df-8992eefdd714)


Working:
1. The main window gives you two options to select from as below:
   ![image](https://github.com/user-attachments/assets/7ef10eea-09bf-491d-b95a-4e81591dcefc)

2.The artist window have these three options:

![image](https://github.com/user-attachments/assets/64816534-2412-453b-8ad8-40922f628f9d)

3. Upon clicking the upload image, artist can upload images as follow:
   ![image](https://github.com/user-attachments/assets/95411400-4feb-47d6-a1d4-64dfe864e852)

4.Upon clicking the search image , this window pops up:
![image](https://github.com/user-attachments/assets/2cac9a86-cf22-486f-8e60-c63c0f466bed)

3.The visitor window shows all the details of painting stored in the database by the artist:

![image](https://github.com/user-attachments/assets/2809aaa2-484c-4632-b7ec-44d71a2c6314)





Database Used:
We have used SQLITE for storing the data as follow:
![image](https://github.com/user-attachments/assets/aa6e89dd-f9c9-4af1-843c-9199ee9074ef)



Build and Run Instructions


Prerequisites:

Install Qt (with qmake tool) from Qt's website.
Install a C++ compiler (e.g., MinGW for Windows, GCC for Linux/macOS).
Ensure make (Linux/macOS) or mingw32-make (Windows) is installed.


Steps:
1. Clone the repository:
           git clone https://github.com/yourusername/artistryconnect.git
           cd artistryconnect
2. Generate Makefiles and build:

Windows (MinGW):
          qmake -project
          qmake
          mingw32-make
Linux/macOS:
         qmake
         make
         

3.Bundle dependencies (Optional for portability):

         Windows: Run windeployqt artistryconnect.exe
         Linux: Run linuxdeployqt artistryconnect -appimage
         macOS: Run macdeployqt artistryconnect.app

         
4.Run the application:

       Windows: Double-click artistryconnect.exe
       Linux: Make AppImage executable: chmod +x artistryconnect.AppImage, then run ./artistryconnect.AppImage
       macOS: Double-click the .app bundle.
