# RunPE Binder & Crypter

### Usage example: [https://streamja.com/3mwKA](https://streamja.com/3mwKA)

It is experimental, if you create a payload, test it before sending it through the internet.  
If you have a bug or question, please open an issue and I can try to solve it.  
This can bind to most .net program sand keep them functioning, even with needed other components.  

Notes:  
1. With RunPE, Admin is not possible, same with adding to startup because it will just add what it injected to startup. (Not your payload itself)  
2. Stub is in C# .net, the victim will inject into itself, so the victim cannot be in native, only .net. however if the payload is native then it can be injected into a native process like vbc.exe or cvtres.exe  
3. If you run into an error while compiling, try download the .NET 3.5 Framework/Runtime, it should solve the error. If not, open an issue.  
  
  
  
![Screenshot](https://github.com/De-eloper/Image-Storage/raw/main/Screenshot.PNG?raw=true)  
  
