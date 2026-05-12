This is my first large enough OOP project. *(Yes this is large enough for me)*

I'm proud that I have done it myself. I accept that I took help, but not from AI, from REAL HUMANS on The C# Player's Guide Discord Server. 

I don't know them by their name, I haven't seen them, yet they are so helpful. I'm grateful to them.

This project will help me get one step closer to learn .NET Core and Freelance.

It was also more about learning ***Problem Solving***.

Thank you **RB Whitaker** - the author of The C# Player's Guide - for writing such a wonderful book.

---

I'm on Debian and x86 CPU architecture.
I have published (which is compiling + linking + packaging for deployment) for both Windows and Linux.
However I haven't tested it on Windows myself.

You can publish it using these commands.

1. Windows 
```dotnet publish Program.cs -r win-x64 -p:PublishSingleFile=true --self-contained true -p:PublishAot=false```

2. Linux
```dotnet publish Program.cs -r linux-x64 -p:PublishSingleFile=true --self-contained true -p:PublishAot=false```
