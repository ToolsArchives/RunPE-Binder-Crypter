# RunPE Binder & Crypter


It is experimental, if you create a payload, test it before sending it through the internet.  
If you have a bug or question, please open an issue and I can try to solve it.  
This can bind to most .net program sand keep them functioning, even with needed other components.  
The Victim is the file that injects into itself, the Payload is the trojan that injects to the process.  
  
Notes:  
1. With RunPE, Admin is not possible, same with adding to startup because it will just add what it injected to startup. (Not your payload itself)  
2. Stub is in C# .net, the victim will inject into itself, so the victim cannot be in native, only .net. however if the payload is native then it can be injected into a native process like vbc.exe or cvtres.exe  
3. If you run into an error while compiling, try download the .NET 3.5 Framework/Runtime, it should solve the error. If not, open an issue.  
4. With custom inject you need to add the name of an executable within the .NET folder, here's a list of executables:  
AppLaunch.exe  
aspnet_compiler.exe  
aspnet_regbrowsers.exe  
aspnet_regiis.exe  
aspnet_regsql.exe  
aspnet_state.exe  
aspnet_wp.exe  
CasPol.exe  
csc.exe  
cvtres.exe  
dfsvc.exe  
dw20.exe  
IEExec.exe  
ilasm.exe  
InstallUtil.exe  
jsc.exe  
MSBuild.exe  
mscorsvw.exe  
ngen.exe  
RegAsm.exe  
RegSvcs.exe  
vbc.exe  
  
  
  
![Screenshot](https://github.com/De-eloper/Image-Storage/raw/main/Screenshot.PNG?raw=true)  
  
