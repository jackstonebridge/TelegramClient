Native Client (NaCl) is an open-source technology for running native compiled code in the browser, with the goal of maintaining the portability and safety that users expect from web applications. Native Client expands web programming beyond JavaScript, enabling you to enhance your web applications using your preferred language.

Google has implemented the open-source Native Client project in the Chrome browser on Windows, Mac, Linux, and Chrome OS. The Native Client Software Development Kit (SDK), itself an open-source project, lets you create web applications that use NaCl and run in Chrome across multiple platforms.

A Native Client web application consists of JavaScript, HTML, CSS, and a NaCl module written in a language supported by the SDK. The NaCl SDK currently supports C and C++; as compilers for additional languages are developed, the SDK will be updated.



Native Client comes in two flavors: traditional (NaCl) and portable (PNaCl). Traditional, which must be distributed through the Chrome Web Store lets you target a specific hardware platform. Portable can run on the open web. A bitcode file that can be loaded from any web server is downloaded to a client machine and converted to hardware-specific code before any execution. For details, see NaCl and PNaCl individually.

Native Client open-source technology is designed to run compiled code securely inside a browser at near-native speeds. Native Client gives web applications some advantages of desktop software. Specifically, it provides the means to fully harness the client’s computational resources for applications such as 3D games, multimedia editors, CAD modeling, client-side data analytics, interactive simulations. Native Client gives C and C++ (and other languages targeting it) the same level of portability and safety as JavaScript.


Security: Protecting the user’s system from malicious or buggy applications through Native Client’s double sandbox model. This model offers the safety of traditional web applications without sacrificing performance and without requiring users to install a plug-in.
