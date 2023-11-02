# Pre-Requisites

There are a few things you need in advance. This is a one time setup!

Optinal but recommended up front: [Visual Studio Code](https://code.visualstudio.com/) (VS-Code).

## Local ATOM

First of all, you need a local ATOM on your machine. There is no need to start the ATOM, but for local debugging Groovy will need to resolve:

* the ATOM’s binaries (Boomi’s Java libraries) and
* the bundled Java Run-Time (JRE).

[Download and install an ATOM](https://help.boomi.com/bundle/integration/page/t-atm-Downloading\_the\_local\_Atom\_installer.html) on your local machine.

![Untitled](<../MGF4Boomi - Groovy for Boomi bfadc9ce63764373816fa22fccd3cdc1/Getting Started 019408ce4279434d934d162b6ed03d4e/Pre-Requisites 7deb11c4cf894c33b76456ab85cad596/Untitled.png>)

Do not forget to copy you installation token:

![Untitled](<../MGF4Boomi - Groovy for Boomi bfadc9ce63764373816fa22fccd3cdc1/Getting Started 019408ce4279434d934d162b6ed03d4e/Pre-Requisites 7deb11c4cf894c33b76456ab85cad596/Untitled 1.png>)

> It is very recommended you install the ATOM in this path: `c:\Program Files\Boomi AtomSphere\LocalAtom\`

![Untitled](<../MGF4Boomi - Groovy for Boomi bfadc9ce63764373816fa22fccd3cdc1/Getting Started 019408ce4279434d934d162b6ed03d4e/Pre-Requisites 7deb11c4cf894c33b76456ab85cad596/Untitled 2.png>)

## Groovy 2.4.13 SDK

Boomi Integration uses **Groovy 2.4.13** to run Groovy scripts (v1.5 is not supported here). And because we want to test and debug all our scripts under the same run-time conditions we need the right Groovy SDK for it.

### PowerShell script to install the right Groovy SDK

[Download `get-groovy.ps1` from GitHub](https://github.com/MarkusSchmidtPro/Boomi.Groovy.ReferenceProject/blob/8022e34655b0c4dd4a641d6f9ec4558e8b60d8a8/bin/get-groovy.ps1)

![Untitled](<../MGF4Boomi - Groovy for Boomi bfadc9ce63764373816fa22fccd3cdc1/Getting Started 019408ce4279434d934d162b6ed03d4e/Pre-Requisites 7deb11c4cf894c33b76456ab85cad596/Untitled 3.png>)

and run in a PowerShell console:

![Untitled](<../MGF4Boomi - Groovy for Boomi bfadc9ce63764373816fa22fccd3cdc1/Getting Started 019408ce4279434d934d162b6ed03d4e/Pre-Requisites 7deb11c4cf894c33b76456ab85cad596/Untitled 4.png>)

### Manual download and installation

Alternatively, you can [download the Groovy SDK](https://archive.apache.org/dist/groovy/2.4.13/distribution/apache-groovy-sdk-2.4.13.zip) v2.4.13 and unzip into `%UserProfile%\.groovy\sdk\groovy-2.4.13`.

![Untitled](<../MGF4Boomi - Groovy for Boomi bfadc9ce63764373816fa22fccd3cdc1/Getting Started 019408ce4279434d934d162b6ed03d4e/Pre-Requisites 7deb11c4cf894c33b76456ab85cad596/Untitled 5.png>)

## A local project folder

You need a local project folder where you store and manage your customer projects. I recommend naming it `BoomiProjects`.

💡 In the following context we will call this folder \`%ProjectRoot%\`.

![Untitled](<../MGF4Boomi - Groovy for Boomi bfadc9ce63764373816fa22fccd3cdc1/Getting Started 019408ce4279434d934d162b6ed03d4e/Pre-Requisites 7deb11c4cf894c33b76456ab85cad596/Untitled 6.png>)

Maybe your G-Drive (Google Drive) is a good place for it. Personally, I have this folder under GIT version control and on drive C.

## JetBrains IntelliJ IDEA - Groovy IDE

The last component you need is a **Groovy IDE**.

I recommend [download and install JetBrains \*IntelliJ IDEA](https://www.jetbrains.com/idea/download/#section=windows)\* (enable the new UI).

The provided project templates have been built for _IntelliJ IDEA_. If you chose another IDE you will have to adjust your project setup according to it.

Start with your first [customer project.](<Setup a customer project a5e8a967b06b4f9d9123b55f72e07145.md>)