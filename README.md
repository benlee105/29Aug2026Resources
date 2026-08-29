# 29 Aug 2026 Resources
Hi there! Below are some resources from my sharing session on 29 Aug 2026.


# My LinkedIn
https://www.linkedin.com/in/benjamin-l-a047b454/  
  
Please connect with me! 
  
I'm happy to chat and help with anything ranging from forensics, threat hunting, pentesting and red teaming!


# Extra Content about Digital Forensics
I ran out of time to include this content into the slides, but I also wanted you to have a look at:
1. Physical tools for Digital Forensics
2. What actual forensics investigations look like.

## Physical tools for Digital Forensics  
To collect evidence, you're going to need some tools to perform forensics **acquisition**
  
### Write Blockers
Below is a photo of **USB, SATA and PCI-e write blockers**, to safely copy out data from suspect machines without making any changes to the device or PC.
  
On really urgent cases, we may need to bring all these write blockers down to perform fast acquisition onsite!

The big tablet looking device at the bottom right of the case is a forensics imager that acquires a forensics image of a storage device (e.g. HDD, SSD, USB device), and saves it to another storage device.
  
<img width="600" height="800" alt="Write_Blockers" src="https://github.com/user-attachments/assets/a2ac2b45-5be1-430f-bd40-ba3ee6773251" />
  
  
### Mobile Acquisition Toolkit
Below is a photo of a **mobile acquisition toolkit**, filled to the brim with all sorts of mobile connector types.

Loads of legacy connectors, because you never know what you might need. Otherwise, the standard nowadays is USB C and Apple's Lightning cable.
  
<img width="800" height="600" alt="Mobile_Acq" src="https://github.com/user-attachments/assets/c9618a72-06f5-434f-b244-0dd2e76a06b3" />

## What actual forensics investigations look like
Let's talk about what investigations in the past, present and near future look like.

### Investigations in the past
Investigations in the past were manual and low level, and you had to have deep knowledge of each artifact.
  
For example, after opening a Word document, a shortcut LNK file is created in C:\Users\<username>\AppData\Roaming\Microsoft\Windows\Recent
  
You would load that LNK file into a Hex editor, pinpoint the specific location in the file where the critical information is, and convert them to timestamps.
  
<img width="580" height="618" alt="image" src="https://github.com/user-attachments/assets/fb538d25-5915-47c6-9e4d-fb890d08582e" />

### Investigations in the present
Investigations in the present are much faster. Run a tool, it extracts everything for you.

You can even script and automate!

<img width="574" height="277" alt="image" src="https://github.com/user-attachments/assets/f846aed2-6b95-4353-ad8b-3792b82096ee" />

### Investigations in the near future
Investigation in the near future could be just throwing forensics artifacts into AI models for information extraction and analysis.

<img width="666" height="362" alt="image" src="https://github.com/user-attachments/assets/da04849f-1b9c-4768-baa6-f90f8dc0326e" />
    
**But** forensics workstations tend to be isolated and not connected to the internet, so you might need to use local offline open weight models instead.
  
**Also** you'll still need to know what forensic artifacts contain what critical information, and how to manually extract that info out yourselves to **verify that the AI model isn't hallucinating or lying to you**
  

# Training Resources
I mentioned some training resources in my sharing session:  
**TryHackMe** - https://tryhackme.com/module/digital-forensics-and-incident-response  
**13Cubed** - https://training.13cubed.com/  
**LetsDefend** - https://app.letsdefend.io/training/lessons/memory-forensics  
**AntiSyphon** - https://www.antisyphontraining.com/course-catalog/
  
I personally recommend starting off with TryHackMe, because subscription price is at a very competitive rate!

Plus if you decide along the way that you want to learn something else other than forensics, their site is packed full of good quality labs.

Talk to me on LinkedIn if want to chat more about training resources!
  
# Posters
**DFIR Fundamentals** - https://www.sans.org/posters/dfir-fundamentals-poster  
**Intro to Windows Forensics** - https://www.sans.org/posters/windows-forensic-analysis-playbook  
**Windows Artifacts (MUST HAVE!)** - https://www.sans.org/posters/windows-forensic-analysis.   
  
There are **loads** more posters in the sans.org website, ranging from Linux, macOS & mobile forensics, to Cloud, Pentesting, Red Teaming and AI content.
  
Download and collect them all, you'll need them in future!
