<img align="right" src="https://raw.githubusercontent.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/main/nabu.png" width="425" alt="Windows 11 Running On A Xiaomi Pad 5">


# Windows no Xiaomi Pad 5

## Dualbooting entre o Android e o Windows

### Pré requesitos
- ```Cérebro```
- ```que o tablet tenha root```
- ```Windows instalado no tablet```
- [```Imagem do UEFI```](https://github.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/releases/download/UEFI/uefi-v3.img)
- [```M3K WOA Helper app```](https://github.com/woa-vayu/WoA-Helper-M3K/releases/latest)
- [```StA Installer```](https://github.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/releases/download/dualboot/StA_Installer_nabu.exe)

## Configurando o app de dualboot
> Esse guia pressupõe que você tem root, caso contrário, siga o [guia de root](2-rootguide-pt.md) primeiro

### Preparação - Android
> [!NOTE]
> Se você não consegue mover arquivos para a pasta Windows, significa que você desligou o Windows ao invés de reiniciar. Pra concertar isso, inicie de volta para o Windows, e enquando ele reinicia, coloque o tablet no modo fastboot e inicie o Android de volta

- Faça o download e instale o [M3K WOA Helper app](https://github.com/woa-vayu/WoA-Helper-M3K/releases/latest), abra, e permita o uso de root.
- Faça o download da [Imagem UEFI](https://github.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/releases/download/UEFI/uefi-v3.img) e coloque na pasta chamada `UEFI` no armazenamento interno, caso essa pasta não exista, você pode criá-la.
- Retorne ao app M3K WOA Helper e pressione a opção `Back up Android boot`. Selecione ambas as opções `Windows` e `Android`.
- Pressione a opção `Mount Windows`, faça o download e mova o arquivo [StA_Installer_nabu.exe](https://github.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/releases/download/dualboot/StA_Installer_nabu.exe) para a pasta `Windows` recém criada no seu armazenamento interno.
- Retorne ao app WOA Helper e pressione `Quickboot to Windows`.

### Preparação - Windows
- Navegue até e abra o programa `C:\StA_Installer_nabu.exe`. Se não funcionar ou abrir, tenha certeza que seu antivírus esteja desligado, já que o mesmo pode atrapalar a instalação do programa.

##### Inicializando o Android
  - Abra o novo atalho na sua área de trabalho (para facilitar o acesso, você pode fixar o programa no menu iniciar / na barra de tarefas).

##### Inicializando o Windows
  - Pressione `Quickboot to Windows` no app, ou adicione o toggle no seu painel de configurações rápidas.
  
## Concluído!

