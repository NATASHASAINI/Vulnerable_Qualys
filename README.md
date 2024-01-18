<b>Nessus Vulnurability Management (Home Lab)</b></br>

<b>Introduction</b></br>
In the realm of cybersecurity, staying ahead of potential vulnerabilities is crucial. One effective tool for vulnerability management is Nessus, a comprehensive solution that helps identify and remediate security weaknesses. In this blog post, we will delve into a recent project where I set up a lab environment to practice with Nessus vulnerability management.

<b>Setting Up the Lab Environment</b></br>
![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/24eabcb4-a7ba-448d-b48c-5558494dc4ff)



<b>Running Credentialed and Non-Credentialed Scans:</b></br>
Next, I ran both a non-credentialed scan and a credentialed scan on the virtual machine. A non-credentialed scan relies solely on network-based techniques to identify vulnerabilities. A credentialed scan involves providing Qualys with administrative access to the target system, enabling a more comprehensive assessment of vulnerabilities.

![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/69449ed6-1bcd-44d8-ba2b-8658e960a002)

<b>Analyzing the Scan Results:</b></br>
After the scans completed, I carefully reviewed the scan results provided by Qualys. The detailed reports highlighted vulnerabilities present in the Windows 11 virtual machine.

The non-credentialed scan revealed some general Network-level vulnarabilities. The results of the credentialed scan put the VM at a Risk level of 3.0/5.0. 
Each vulnarability identified has detailed descriptions of the potential threat and impact, as well as providing you with its Common Vulnarabilities & Exposure (CVE) index number. They also provide steps for remediation.The credentialed scan, on the other hand, categorized the VM as a full 5.0 Security Risk. The vast majority of these are referring to the outdated versions of FireFox and VLC

![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/ba780c5e-01af-4d04-bca1-76fed1711b14)

![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/6a37b716-583c-4527-95ef-edf11b2a611f)



<b>Optimizing Scan Results for Remediation:</b></br>
With the vulnerability information at hand, I could proceed with the remediation process. In a normal SOC environment, you wouldn't normally have the Security Analyst who is running the vulnarability scan also do the remediations, due to seperation of duties, instead they would normally present this information to the respective subject matter expert. By applying the necessary updates, I effectively reduced the vulnerability exposure of the virtual machine.

![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/7f4dd133-a80a-459b-b12d-0290345558d6)

Analayze Reports

![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/c7f0e9fc-c5c0-48cc-bd24-2d8b1ca5f27b)
![image](https://github.com/NATASHASAINI/Vulnerable_Qualys/assets/156629309/03ba64f3-bf9b-45d0-a983-f34f1d82aded)


<b>Conclusion:</b></br>
In this project, I had the opportunity to explore Qualys vulnerability management by setting up a lab environment, installing outdated software versions, and running both credentialed and non-credentialed scans. By analyzing the scan results and following the recommendations provided, I successfully remediated the vulnerabilities identified in the Windows 11 virtual machine. Through this hands-on experience, I gained valuable insights into the power and effectiveness of Qualys in mitigating potential security risks.

