# Hello world tutorial
This tutorial is based on [Microsort .Net Official Document](https://dotnet.microsoft.com/learn/dotnet/hello-world-tutorial/intro)

# Download and install on Mac
1. Install .Net core SDK using Homebrew
    ```brew cask install dotnet-sdk```
2. Check everything installed correctly.
    ```dotnet```
3. Check your .Net Core SDK version.
    ```dotnet --version```
4. Install C# Extensions on vscode.
    [C# for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)

# Create your app
1. In your terminal, run the following commands:
    ```dotnet new console -o helloWorldApp
    cd helloWorldApp```
    ![tutorial create_your_app](https://dotnet.microsoft.com/images/tutorial-gifs/dotnet-hello-world-create-app.gif)

2. Check initial C# program.
    ```cat Program.cs```
    ```using System;
    
    namespace myApp
    {
        class Program
        {
            static void Main(string[] args)
            {
                Console.WriteLine("Hello World!");
            }
        }
    }
    ```

# Run your app
1. In your terminal, run the following command:
    ```dotnet run```
    ![tutorial run_app](https://dotnet.microsoft.com/images/tutorial-gifs/dotnet-hello-world-run-app.gif)

# Edit your code
1. Open `Program.cs` in vscode and add a new line of code below the one that prints "Hello World!", like the following:
    ```Console.WriteLine("Hello World!");
    Console.WriteLine("The current time is " + DateTime.Now);
    ```
2. Save the `Program.cs` file, and run your code again.
    ```dotnet run```

# Keep learning
1. If you want to keep learning general .NET skills, try our Introduction to C# tutorials.
    [Manipulate integral and floating point numbers in C#](https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/intro-to-csharp/numbers-in-csharp-local)
2. .NET Core using CLI.
    [Get started with .NET Core on Windows/Linux/macOS using the command line]({)https://docs.microsoft.com/en-us/dotnet/core/tutorials/using-with-xplat-cli)