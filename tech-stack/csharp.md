# C# (ASP.NET) Setup 

> Install the `SDK`:

```bash
sudo pacman -S dotnet-sdk

# or 

sudo install -y dotnet-sdk
```
> Install the runtime:

```bash
sudo pacman -S aspnet-runtime

# or

sudo install -y aspnet-runtime
```
> Start a project with 'ASP.NET Core Web API or MVC':

```bash
# Web API 
dotnet new web-api -n <project_name>

# MVC 
dotnet new mvc -n <project_name>
```
> Build and Run the project: 

```bash
dotnet build ; dotnet run
```




