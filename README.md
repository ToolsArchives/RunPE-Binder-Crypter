# RunPE-Binder-Crypter

### Tutorial video on how to use example: [https://streamja.com/3mwKA](https://streamja.com/3mwKA)

it is experimental, if you create a payload make sure to test it before sending it through internet.
if you have bugs or question open an issue and i can try to solve it.
this can bind to most .net program and keep them functioning, even with needed other components.

.:: NOTES: when you use runpe, uac/admin privilege is not possible, same with adding to startup because it will just add what it injected to startup (not payload itself),

.:: NOTES: the stub is in .net, the victim will inject into itself, so the victim cannot be in native, only .net. however the payload can be injected into a native process like vbc.exe or cvtres.exe

![alt text](https://github.com/De-eloper/RunPE-Binder-Crypter/raw/main/screenshot.PNG)

