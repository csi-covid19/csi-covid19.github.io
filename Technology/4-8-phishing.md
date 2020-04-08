4/8 email

----

AA20-099A: COVID-19 Exploited by Malicious Cyber Actors
04/08/2020 08:00 AM EDT

Original release date: April 8, 2020
Summary

This is a joint alert from the United States Department of Homeland Security (DHS) Cybersecurity and Infrastructure Security Agency (CISA) and the United Kingdom’s National Cyber Security Centre (NCSC).

This alert provides information on exploitation by cybercriminal and advanced persistent threat (APT) groups of the current coronavirus disease 2019 (COVID-19) global pandemic. It includes a non-exhaustive list of indicators of compromise (IOCs) for detection as well as mitigation advice.

Both CISA and NCSC are seeing a growing use of COVID-19-related themes by malicious cyber actors. At the same time, the surge in teleworking has increased the use of potentially vulnerable services, such as virtual private networks (VPNs), amplifying the threat to individuals and organizations.

APT groups and cybercriminals are targeting individuals, small and medium enterprises, and large organizations with COVID-19-related scams and phishing emails. This alert provides an overview of COVID-19-related malicious cyber activity and offers practical advice that individuals and organizations can follow to reduce the risk of being impacted. The IOCs provided within the accompanying .csv and .stix files of this alert are based on analysis from CISA, NCSC, and industry.

Note: this is a fast-moving situation and this alert does not seek to catalogue all COVID-19-related malicious cyber activity. Individuals and organizations should remain alert to increased activity relating to COVID-19 and take proactive steps to protect themselves.

Technical Details

Summary of Attacks

APT groups are using the COVID-19 pandemic as part of their cyber operations. These cyber threat actors will often masquerade as trusted entities. Their activity includes using coronavirus-themed phishing messages or malicious applications, often masquerading as trusted entities that may have been previously compromised. Their goals and targets are consistent with long-standing priorities such as espionage and “hack-and-leak” operations.

Cybercriminals are using the pandemic for commercial gain, deploying a variety of ransomware and other malware.

Both APT groups and cybercriminals are likely to continue to exploit the COVID-19 pandemic over the coming weeks and months. Threats observed include:

Phishing, using the subject of coronavirus or COVID-19 as a lure,
Malware distribution, using coronavirus- or COVID-19- themed lures,
Registration of new domain names containing wording related to coronavirus or COVID-19, and
Attacks against newly—and often rapidly—deployed remote access and teleworking infrastructure.
Malicious cyber actors rely on basic social engineering methods to entice a user to carry out a specific action. These actors are taking advantage of human traits such as curiosity and concern around the coronavirus pandemic in order to persuade potential victims to:

Click on a link or download an app that may lead to a phishing website, or the downloading of malware, including ransomware.
For example, a malicious Android app purports to provide a real-time coronavirus outbreak tracker but instead attempts to trick the user into providing administrative access to install "CovidLock" ransomware on their device.[1]
Open a file (such as an email attachment) that contains malware.
For example, email subject lines contain COVID-19-related phrases such as “Coronavirus Update” or “2019-nCov: Coronavirus outbreak in your city (Emergency)”
To create the impression of authenticity, malicious cyber actors may spoof sender information in an email to make it appear to come from a trustworthy source, such as the World Health Organization (WHO) or an individual with “Dr.” in their title. In several examples, actors send phishing emails that contain links to a fake email login page. Other emails purport to be from an organization’s human resources (HR) department and advise the employee to open the attachment.

Malicious file attachments containing malware payloads may be named with coronavirus- or COVID-19-related themes, such as “President discusses budget savings due to coronavirus with Cabinet.rtf.”

Note: a non-exhaustive list of IOCs related to this activity is provided within the accompanying .csv and .stix files of this alert.

Phishing

CISA and NCSC have both observed a large volume of phishing campaigns that use the social engineering techniques described above.

Examples of phishing email subject lines include:

2020 Coronavirus Updates,
Coronavirus Updates,
2019-nCov: New confirmed cases in your City, and
2019-nCov: Coronavirus outbreak in your city (Emergency).
These emails contain a call to action, encouraging the victim to visit a website that malicious cyber actors use for stealing valuable data, such as usernames and passwords, credit card information, and other personal information.

SMS Phishing

Most phishing attempts come by email but NCSC has observed some attempts to carry out phishing by other means, including text messages (SMS).

Historically, SMS phishing has often used financial incentives—including government payments and rebates (such as a tax rebate)—as part of the lure. Coronavirus-related phishing continues this financial theme, particularly in light of the economic impact of the epidemic and governments’ employment and financial support packages. For example, a series of SMS messages uses a UK government-themed lure to harvest email, address, name, and banking information. These SMS messages—purporting to be from “COVID” and “UKGOV” (see figure 1)—include a link directly to the phishing site (see figure 2).

