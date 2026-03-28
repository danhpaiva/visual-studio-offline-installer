# Visual Studio 2026 v18.0.1

Esta ISO contém:
.NET Desktop, .NET Web, SDK 10

Pós-Install 
1.	Realizar login com conta da Microsoft
2.	Desabilitar Updates:
	Ferramentas > Opções > Atualizações de Produto > Baixar Atualizações Automaticamente
3.	Fonts
	Instalar JetBrains Mono ou usar Cascadia Code


### MONTE SUA ISO

.NET Desktop | .NET Web | Processamento e armazenamento de dados

~~~
 .\vs_Community.exe --layout D:\vs --add Microsoft.VisualStudio.Workload.ManagedDesktop --add Microsoft.VisualStudio.Workload.NetWeb --add Microsoft.VisualStudio.Workload.Data --includeOptional --lang en-US
~~~

Obs.: Se atente para os traços do comando para não ter erro ao copiar e colar no terminal.
Melhor deixar o comando em uma única linha pelo Notepad++.

### Referências

https://learn.microsoft.com/pt-br/visualstudio/install/create-an-offline-installation-of-visual-studio

https://learn.microsoft.com/pt-br/visualstudio/install/create-a-network-installation-of-visual-studio

https://learn.microsoft.com/en-us/visualstudio/install/workload-component-id-vs-community?view=visualstudio

https://learn.microsoft.com/en-us/visualstudio/releases/2026/release-notes
