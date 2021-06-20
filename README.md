# .NET-API

<h3>Projeto de conclusão do bootcamp da Digital Innovation One em parceria com a Localiza Labs com o objetivo de criar de uma API RESTtful utilizando .NET e C#.</h3>

Para executá-lo, basta instalar o .NET 5 eu seu sistema operacional, vide: 
<ul>

<li>Linux: <a href="https://docs.microsoft.com/pt-br/dotnet/core/install/linux-ubuntu" target="_blank">https://docs.microsoft.com/pt-br/dotnet/core/install/linux-ubuntu</a></li>

<li>Windows: <a href="https://docs.microsoft.com/pt-br/dotnet/core/install/windows" target="_blank">https://docs.microsoft.com/pt-br/dotnet/core/install/windows</a></li>

<li>MAC: <a href="https://docs.microsoft.com/pt-br/dotnet/core/install/macos" target="_blank">https://docs.microsoft.com/pt-br/dotnet/core/install/macos</a></li>

</ul>

Após instalar, execute:

```console

$ dotnet restore
$ dotnet build
$ dotnet run

```
<b>Observação:</b> será necessário criar um cluster na plataforma do <a href="https://www.mongodb.com/" target="_blank">MongoDB</a> e colar sua string de conexão no arquivo: <i>appsettings.json</i>, mais especificamente no campo "ConnectionString".