### Role of IDE in JS/TS Backend Development

A good IDE provides suggestions for "code completion", validates code syntax and structure, helps navigating through the code components, offers code editing and refactoring tools. Traditionally, IDE is also used by developers to execute code for testing and step-by-step debugging. 

A good developer writes simple, clear, easily understood code. Arguably, such a code does not require debugging. This is a particularly good news for JS backend developers, because an effective step-by-step debugging of inherently asynchronous and multi-component systems is hard. Instead, a flexible and detailed "debug" level *logging* is the method that replaces the IDE built-in debugger engine. 

When Docker is used in development, the runtime execution environment is present in containers only, not on the host, so the debugger engine would not be available in the host-based IDE. Some systems enable *remote* debugging, but again, if the platform is robust and code is clear - simple logging does the job. Don't waste your time configuring remote debugging - spend it on improving your coding skills.

Fundamentally, containerization allows constructing environments hosted anywhere where network connectivity exists, so the concept of an *online* IDE for professional development work fits perfectly well into the process. Of course, assuming that the connectivity between the physical dev workstation and the online IDE is available all the time and at a very low latency. Whether you put your dev environment computing power and the file system right next to your monitors, keyboard and mouse (as in the laptop scenario) or in the cloud - depends on the cost-productivity calculation.

### The Power of Microsoft Visual Studio Code (VSC)

[Visual Studio Code](https://code.visualstudio.com/) is a relatively light-weight IDE compare to the likes of Eclipse or [JetBrains](https://www.jetbrains.com/) IDE products. It is free, comes with a variety of features, runs on any laptop OS and even supports multi-developer [live screen shares](https://visualstudio.microsoft.com/services/live-share/). 

Keep in mind that as JS is a loosely structured language, intelligent capabilities of any IDE are limited when coding in it (although, TS adds more structure and therefore gives more power to the IDE). So, when it comes to backend JS development, a "fancier" IDE would not give you much extra compare to a basic one. No wonder, a sizeable number of professional developers get by without an IDE at all and develop in plain text editors like Vim. 

Install VSC if you haven't already done so - it's a great tool, you won't regret. However, this course doesn't require you using a specific IDE - any code writing tool will do. In the end - the code is written by the developer, not by the IDE.

You may want to disable VSC default "Preview Mode" (so that files you opened stay open) and configure auto-save: the "Save" button is such an antiquated way of handling computer work. 
<br>
The last tool to install is MongoDB Compass - next