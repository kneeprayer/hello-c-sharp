# Hello world tutorial
This tutorial based on [Microsort .Net Official Document](https://dotnet.microsoft.com/learn/dotnet/hello-world-tutorial/intro)

# Download and install on Mac
1. Install .Net core SDK using Homebrew
`brew cask install dotnet-sdk`
2. Check everything installed correctly.
`dotnet`
3. Install C# Extensions on vscode
[C# for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)

# Create your app
1. In your terminal, run the following commands:
`dotnet new console -o helloWorldApp`
`cd helloWorldApp`
![tutorial create_your_app](https://dotnet.microsoft.com/images/tutorial-gifs/dotnet-hello-world-create-app.gif)

`cat << EOF > helloworld.cs`
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
EOF
```
`cat helloworld.cs`
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
`dotnet run`
![tutorial run_app](https://dotnet.microsoft.com/images/tutorial-gifs/dotnet-hello-world-run-app.gif)

# Edit your code
1. Open `helloworld.cs` in vscode and add a new line of code below the one that prints "Hello World!", like the following:
```Console.WriteLine("Hello World!");
Console.WriteLine("The current time is " + DateTime.Now);
```
2. Save the `helloworld.cs` file, and run your code again.
`dotnet run`

# Keep learning
If you want to keep learning general .NET skills, try our Introduction to C# tutorials.
[Manipulate integral and floating point numbers in C#](https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/intro-to-csharp/numbers-in-csharp-local)