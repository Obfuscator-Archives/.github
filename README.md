# .NET-Obfuscator

>.NET Obfuscator is a tool that is used to protect .NET applications from reverse engineering. 

* This is done by **transforming the original .NET code into a form that is difficult to understand**, making it hard for attackers to decompile the code and understand how it works. 

* This can help to **prevent the theft of intellectual property** and also protect against potential security vulnerabilities. 

* **Obfuscation** can also help to reduce the size of the code, which can improve the performance of the application.

Here is an example of a simple C# program that calculates the factorial of a given number:
```csharp
using System;

namespace FactorialCalculator
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Enter a number:");
            int num = int.Parse(Console.ReadLine());
            int factorial = 1;

            for (int i = 1; i <= num; i++)
            {
                factorial *= i;
            }

            Console.WriteLine("The factorial of {0} is {1}", num, factorial);
        }
    }
}
```

To obfuscate this code, a .NET Obfuscator would transform it into something like this:
```csharp
using System;

namespace XZkxcX
{
    class XxXXx
    {
        static void XxXXX(string[] XxxxX)
        {
            Console.WriteLine("Enter a number:");
            int XxXx = int.Parse(Console.ReadLine());
            int XXXXXXX = 1;

            for (int XxXX = 1; XxXX <= XxXx; XxXX++)
            {
                XXXXXXX *= XxXX;
            }

            Console.WriteLine("The factorial of {0} is {1}", XxXx, XXXXXXX);
        }
    }
}
```
As you can see, the obfuscated code is much harder to understand and follow, making it difficult for someone to reverse engineer the original code.

(__Info can include websites, comments, links and more.. If it's a "tree" or using sub-schema, it mean fork or skidding ! Also it's sorted in Alphabetic order(depending if it's authentic or no).__)
<br><br>Note: __Mainly .Net so any nummber of `°` mean another target language__<br>
°) Lua


  - ["Simple" Obfuscators/Others](#Others)
  - [ConfuserEx Based](#ConfuserEx-Based)
  - [VMs Based/Virtualization](#VMs)
  
  - [FAQ](#FAQ)

### Others
- [Kov.NET](https://github.com/Obfuscator-Archives/Kov.NET)
  - [KOV.NET-Modded](https://github.com/Obfuscator-Archives/KOV.NET-Modded)
- [Krawk-Protector](https://github.com/Obfuscator-Archives/Krawk-Protector)
- [LoGiC.NET](https://github.com/Obfuscator-Archives/LoGiC.NET)
- [MindLated](https://github.com/Obfuscator-Archives/MindLated)
  - [Aura](https://github.com/Obfuscator-Archives/Aura) | [Skidded](https://github.com/loomisntreal/Aura-.NET-Obfuscator/pull/2)
- [NetShield](https://github.com/Obfuscator-Archives/NetShield)
- [OliviaGuard](https://github.com/Obfuscator-Archives/OliviaGuard) | "Created" originaly for a obfuscator website([Showcase Vido](https://youtu.be/s3qeLnkk10s))
- [ScoldProtect](https://github.com/Obfuscator-Archives/ScoldProtect)

### ConfuserEx-Based
- [Original ConfuserEx](https://github.com/Obfuscator-Archives/ConfuserEx) | By [yck1509](https://github.com/yck1509)
  - [198-Protector-v4](https://github.com/Obfuscator-Archives/198-Protector-v4)
  - [ConfuserEx-Mod-By-Beds](https://github.com/Obfuscator-Archives/ConfuserEx-Mod-By-Beds)
  - [DarksProtector](https://github.com/Obfuscator-Archives/DarksProtector) | (Linked to [DarksVM](https://github.com/Obfuscator-Archives/DarksVM))
  - [GalaxyProtector](https://github.com/Obfuscator-Archives/GalaxyProtector)
  - [ModPhuserEx](https://github.com/Obfuscator-Archives/ModPhuserEx)
  - [RzyProtector](https://github.com/Obfuscator-Archives/RzyProtector)
  - [SkiDzEX](https://github.com/Obfuscator-Archives/SkiDzEX)
  - [Trinity-ConfuserEx-Mod](https://github.com/Obfuscator-Archives/Trinity-ConfuserEx-Mod)
- [Kind Of Official ConfuserEx Fork](https://github.com/Obfuscator-Archives/ConfuserEx-mkaring) | See [this](https://github.com/yck1509/ConfuserEx/issues/671) issue for ref(added to the README of `ConfuserEx` by `yck1509`)

### VMs
- [CawkVM](https://github.com/Obfuscator-Archives/CawkVM) | Well I feel like we can more talk about `Dynamic Methods` here
- [Hex-Virtualization](https://github.com/Obfuscator-Archives/Hex-Virtualization) | `Built so that people can learn from it` (Showing 1:1 & Custom OpCodes)
- [ILVirtualization](https://github.com/Obfuscator-Archives/ILVirtualization)
- [IronBrew2](https://github.com/Obfuscator-Archives/IronBrew2-DefCon42) | ° (Found `DefCon42` = original creator or at least core maintainer ?)
  - [Supposed IronBrew2](https://github.com/Obfuscator-Archives/IronBrew2) | °
- [KoiVM](https://github.com/Obfuscator-Archives/KoiVM) | By [yck1509](https://github.com/yck1509)
  - [KoiVM-Wich-ConfuserEx](https://github.com/Obfuscator-Archives/KoiVM-Wich-ConfuserEx)
  - [KoiVM-No-ConfuserEx](https://github.com/Obfuscator-Archives/KoiVM-No-ConfuserEx)
  - [AndyLarkinsVM](https://github.com/Obfuscator-Archives/AndyLarkinsVM)
  - [AstroNet](https://github.com/Obfuscator-Archives/AstroNet)  
  - [DarksVM](https://github.com/Obfuscator-Archives/DarksVM) | (Linked to [DarksProtector](https://github.com/Obfuscator-Archives/DarksProtector))
  - [MaMoVM](https://github.com/Obfuscator-Archives/MaMoVM)
  - [RinProtector](https://github.com/Obfuscator-Archives/RinProtector)
  - [SupremeVM](https://github.com/Obfuscator-Archives/SupremeVM)
- [MemeVM](https://github.com/Obfuscator-Archives/MemeVM)
- [NashaVM](https://github.com/Obfuscator-Archives/NashaVM)
- [VMProtect 3.5.x](https://github.com/Obfuscator-Archives/VMProtect_3.5) | [Website](https://vmpsoft.com) | A Popular And Strong VM Based Obfuscator

### FAQ
<details>
    <summary>
        Did you modify one of these code before publishing ?
    </summary>
    Well, good question.. No, if I have to be serious, no, all the codes has been left as-is and should be free of malware.
</details>
<details>
    <summary>
        Can I support the project ?
    </summary>
    Yes, you can either "sponsor" me with the button on my profile (https://github.com/TheHellTower) or donate by going there: https://github.com/TheHellTower#-support-my-work and read, click here to see my Discord or other social to contact me: https://github.com/TheHellTower#-socials.
</details>
<details>
    <summary>
        Can you make me a custom obfuscator/protector with everything I need ?
    </summary>
    Yes and no, I can't just do that and see a bunch of people in my DMs. However, You can send me an email at: "thehelltower@tuta.io" with your offer(price + (A Mod of existing ones or from scratch(Created from 0)) + details such as features, including a VM or no with internal details, if you want the source code, etc..) and we will see together what can be done and would suit your needs !

    Note: Support for 48 hours included(Nice offer = Extended support).
</details>
<details>
    <summary>
        I have a question, can I contact you ?
    </summary>
    Yes you can either by opening a issue: https://github.com/Obfuscator-Archives/.github/issues/new or send me an email at: "thehelltower@tuta.io" or contact me on one of my socials here: https://github.com/TheHellTower#-socials

    Note: Only for questions and business inqueries no code support.
</details>
