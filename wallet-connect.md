using Neo.SmartContract.Framework;
using Neo.SmartContract.Framework.Services.Neo;
using Neo.SmartContract.Framework.Services.System;

public class HelloWorld : SmartContract
{
    public static string Main(string name)
    {
        return "Hello, " + name + "!";
    }
}