# DarkClass
Bu MemoryClass Script tarafindan hazirlanmistir

# Kullanimi
> DarkMem memclass;

> process = memclass.getProcess("csgo.exe")

>  gameModule = memclass.getModule(process, "client.dll");

# ReadMemory
>	localPlayer = memclass.readMem<DWORD>(gameModule + lPlayer);

# WriteMemory
> memclass.writeMem<DWORD>(gameModule + fJump, 6);


