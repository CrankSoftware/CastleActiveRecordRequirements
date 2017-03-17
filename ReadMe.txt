To pack the nuget package:

1.

	Install the nuget cli - https://docs.microsoft.com/en-us/nuget/guides/install-nuget

	If you have Chocolatey:
	bash: choco install nuget.commandline

2. 

	Within command line, CD tot this directory

3.

	bash: nuget pack CastleActiveRecordRequirements.csproj -Prop Configuration=Release