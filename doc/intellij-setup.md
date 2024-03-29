---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 0⃣ IntelliJ - First Time Setup

Run IntelliJ IDEA and open your first _Scripts_ project

<div align="left">

<figure><img src=".gitbook/assets/Untitled.png" alt=""><figcaption></figcaption></figure>

</div>

IntelliJ IDEA will probably complain about not yet knowing the global libraries and SDKs.

<figure><img src=".gitbook/assets/Untitled 1.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
<mark style="color:red;">**Do not**</mark> **click on these yellow bars!** We will setup manually!!!
{% endhint %}

### Three things to do

<details>

<summary>Configure the ATOMSphere JDK</summary>

*   Open the Module settings or press F4 \
    **Platform Settings** → **SDKs** → **+** → **Add JDK …**\


    <div align="left">

    <figure><img src=".gitbook/assets/Untitled 2.png" alt="" width="491"><figcaption></figcaption></figure>

    </div>

<!---->

*   then add `C:\Program Files\Boomi AtomSphere\LocalAtom\jre`\
    and name it _`AtomSphere`_\


    <figure><img src=".gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary>Configure Groovy SDK 2.4.13</summary>

![](<.gitbook/assets/Untitled 4.png>)

Use **Library → Create … → Choose Groovy SDK** location

![](<.gitbook/assets/Untitled 5 (2).png>)

Close the dialog → **OK** and stop! A project library can be used only in the current project. However, we want to use the Groovy SDK in all future projects. That's why we want to **configure it as a global library**.

![](<.gitbook/assets/Untitled 6.png>)

![](<.gitbook/assets/Untitled 7.png>)

</details>

<details>

<summary>Add the ATOMSphere libraries</summary>

In your Project Dialog (F4) add a **New Global Library Java** `C:\Program Files\Boomi AtomSphere\LocalAtom\lib`

<img src=".gitbook/assets/Untitled 8.png" alt="" data-size="original">

Add it to all Modules

![](<.gitbook/assets/Untitled 9.png>)

And, finally, give it a more meaningful name

![](<.gitbook/assets/Untitled 10.png>)

</details>

<figure><img src=".gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

You are ready to go with IntelliJ and you can start debugging the _HelloWorldTest_ script -> [first-steps](first-steps/ "mention")
