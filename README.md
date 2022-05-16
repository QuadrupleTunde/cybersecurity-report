# Cybersecurity-report

## Microsoft Exchange Server breach-2021
---

#### What type of attack was this?
***
Ransomware, malware, crypto-mining and other nefarious cyberattacks are only symptoms of the initial Microsoft Exchange breach. 

#### How was the vulnerability discovered?
***
Since early January 2021, security researchers and independent labs detected several critical vulnerabilities within Microsoft’s Exchange Server software. These vulnerabilities allowed hackers, believed to be the Chinese-affiliated group HAFNIUM, to gain access to exchange servers using server-side request forgeries, insecure deserialization, and arbitrary file writing.

#### How were the attackers able to exploit the vulnerability?
***
This access enabled the hackers to create accounts, redirect data and emails, and laterally move within the server environment. Critically, the timing of these events reveals how the breach went from bad to worse: research labs DEVCORE and Volexity identified vulnerabilities and alerted Microsoft in early January 2021.
Once each of these organizations acted and Microsoft prepared to issue a patch, HAFNIUM escalated their attack tempo to identify as many servers vulnerable to their tools as possible. Ultimately, this has resulted in several reports identifying about 30,000 organizations in the U.S. suffering a compromise. Post-compromise tools such as Covenant, Nishang and PowerCat were deployed, enabling remote access. In some cases, the ransomware known as DearCry was subsequently installed on vulnerable on-premises Microsoft Exchange servers. The REvil ransomware was also deployed on other vulnerable systems, as was the Black KingDom ransomware.
The breach technique:
    They used server-side request forgeries to run commands beyond its intended permissions, including self-authentication, to gain access into Exchange Servers.
  They transferred files out via insecure deserialization. Simply, serialization is a process where blocks of code are summarized for easier reference when writing other sections of code. Insecure deserialization is a process of decoupling that association and, in this case, running any code they desired.
  Finally, hackers exfiltrated data and emails using arbitrary file writing, a vulnerability where attackers write to files anywhere within the server regardless of permissions or accesses granted.

#### Were there security measures that could have been taken in order to prevent this attack?
***
This breach illustrates the volume of organizations still using legacy systems and the security benefits of migrating to a cloud service with a cybersecurity advisor’s support. It also highlights the dedication needed to keep on-premise systems secure. Patching, updating, and managing vulnerabilities and functionality for physical equipment is a significant undertaking.

The decision between moving services to the cloud or keeping them on-premises is complex, and every organization will face different requirements for data protection and availability. However, on-premise equipment has the added challenge of requiring updates and patch management.

Moreover, updates and maintenance are not only for security but for the basic functionality of a server running Exchange. With on-premises equipment, it’s the organization’s responsibility to manage and prioritize what updates are issued, how, and when based on bandwidth, necessity, and regulatory requirements.

