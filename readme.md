# Cybersecurity-report

## Equifax data breach -2017
---
## What type of attack was this?
Scareware, spare phishing, malware.

## How was the vulnerability discovered?
***
The data breach into Equifax was principally through a third-party software exploit that had been patched, and Equifax failed to update their servers with it. Equifax had been using the open-source Apache Struts as its website framework for systems handling credit disputes from consumers. A key security patch for Apache Struts was released on March 7, 2017 after a security exploit was found and all users of the framework were urged to update immediately. Security experts found an unknown hacking group trying to find websites that had failed to update Struts as early as March 10, 2017 as to find a system to exploit. The United States Department of Justice announced on February 10, 2020 that they had indicted four members of China's military on nine charges related to the hack, though there has been no additional evidence that China has since used the data from the hack. The Chinese government denied that the four accused had any involvement with the hack.

## How were the attackers able to exploit the vulnerability?
***
As determined through postmortem analysis, the breach at Equifax started on May 12, 2017 when Equifax had yet to update its credit dispute website with the new version of Struts. The hackers used the exploit to gain access to internal servers on Equifax' corporate network. The information first pulled by the hackers included internal credentials for Equifax employees, which then allowed the hackers to search the credit monitoring databases under the guise of an authorized user. Using encryption to further mask their searches, the hackers performed more than 9000 scans of the databases, extracted information into small temporary archives that were then transferred off the Equifax servers to avoid detection and removed the temporary archives once complete. The activities went on for 76 days until July 29, 2017 when Equifax discovered the breach and subsequently, by July 30, 2017, shut off the exploit. At least 34 servers in twenty different countries were used at different points during the breach, making tracking the perpetrators difficult. While the failure to update Struts was a key failure, analysis of the breach found further faults in Equifax' system that made it easy for the breach to occur, including the insecure network design which lacked sufficient segmentation, potentially inadequate encryption of personally identifiable information (PII), and ineffective breach detection mechanisms.

Information accessed in the breach included first and last names, Social Security numbers, birth dates, addresses and, in some instances, driver's license numbers for an estimated 143 million Americans, based on Equifax' analysis. Information on an estimated range of under 400,000 up to 44 million British residents as well as 8,000 Canadian residents were also compromised. An additional 11,670 Canadians were affected as well, later revealed by Equifax. Credit card numbers for approximately 209,000 U.S. consumers, and certain dispute documents with personally identifiable information for approximately 182,000 U.S. consumers were also accessed.

Since the initial disclosure in September 2017, Equifax expanded the number of records they discovered were accessed. In both October 2017 and March 2018, Equifax reported that an additional 2.5 and 2.4 million American consumer records were accessed, respectively, bringing the total to 147.9 million. Equifax narrowed its estimate for UK consumers affected by the breach to 15.2 million in October 2017, of which 693,665 had sensitive personal data disclosed. Equifax also estimated that the number of drivers' licenses breached in the attack to be 10-11 million.

Security experts expected that the lucrative private data from the breach would be turned around and sold on black markets and the dark web, though as of May 2021, there has been no sign of any sale of this data. Because the data did not immediately show up in the first 17 months following the breach, security experts theorized that either the hackers behind the breach were waiting for a significant amount of time before selling the information since it would be too "hot" to sell that close to the breach, or that a nation-state was behind the breach and planning on using the data in a non-financial manner such as for espionage.

## Were there security measures that could have been taken in order to prevent this attack?
***
The Equifax breach that exposed sensitive data for as many as 143 million US consumers was accomplished by exploiting a Web application vulnerability that had been patched more than two months earlier, officials with the credit reporting service said Thursday.

The disclosure strongly suggests that Equifax failed to update its Web applications, despite demonstrable proof that the bug gave real-world attackers an easy way to take control of sensitive sites. An Equifax representative didn't immediately respond to an e-mail seeking comment on this possibility.
