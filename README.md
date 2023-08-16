# IM App Traffic Analysis Project

Welcome to the IM App Traffic Analysis Project! This project aims to delve into the world of Instant Messaging (IM)
apps, exploring their traffic patterns to uncover potential security vulnerabilities and privacy concerns. Our goal is
to provide valuable insights into the security landscape of these apps, ultimately contributing to a safer digital
communication environment.

## Project Overview

In this project, we analyze data collected from various IM apps to examine their traffic behavior. We investigate
whether the perceived security of these apps aligns with the actual security measures in place. By studying the patterns
and interactions within the traffic, we aim to raise awareness about potential privacy risks and vulnerabilities that
might compromise user data.

## Key Features

- Data Collection: Gather traffic data from a diverse range of IM apps.
- Traffic Analysis: Thoroughly analyze traffic patterns, encryption protocols, and security measures.
- Vulnerability Identification: Identify potential security vulnerabilities and privacy risks.
- Insights and Findings: Share insights and findings with the community through documentation and reports.

## Getting Started
### Basic Instractions
<ol class="getting-started-list">
    <li>Clone the repository:
        <pre><code class="language-sh">git clone https://github.com/LielYoash/NetworksFInalProject.git</code></pre>
    </li>
    <li>Installation:
        <ul>
            <li><strong>Install Wireshark:</strong> Download and install Wireshark from <a href="https://www.wireshark.org/" target="_blank">wireshark.org</a>.</li>
            <li><strong>Install Python Interpreter:</strong> If not already installed, get Python from <a href="https://www.python.org/" target="_blank">python.org</a>.</li> preferably Python version 10
        </ul>
    </li>
<li>Data Collection:
        <ul>
            <li>Open Wireshark and start capturing network traffic.</li>
            <li>Use relevant filters to capture traffic from the IM apps you want to analyze.</li>
        </ul>
    </li>
    <li>Analysis:
        <ul>
            <li>Review captured data using Wireshark to identify relevant packets.</li>
            <li>Utilize Python scripts in this repository to process captured data:</li>
            Choose one out of the 3 paths:
                <ul>
                <li>Export a size by time graph</li>
                <li>Export a PDF graph</li>
                <li>Export a CCDF graph</li>
                </ul>
        <li>Run the program.</li>
       </ul>
    </li>
    <li>Results:
        <ul>
            <li>Visualize findings and insights from the analysis using graphs and charts.</li>
            <li>Document your observations and conclusions in reports or documentation.</li>
        </ul>
    </li>
</ol>

## Findings
    
### Research 
After reading and understanding the thesis of the article, we chose to examine the countermeasures
for analysis attacks on Whatsapp Web.

In Order to examine Whatsapp Web's defences we recorded using Wireshark several occurrences:
1. Sending 3 text messages in a single group, whilst sniffing packets in the wireshark program.
2. Sending 3 pictures in a single group, whilst sniffing packets in the wireshark program.
3. Sending 3 videos in a single group, whilst sniffing packets in the wireshark program.
4. Sending 3 audio files and 3 files in a single group, whilst sniffing packets in the wireshark program.
5. sending all of the above at once, whilst sniffing packets in the wireshark program.

for each occurrence we extracted the data from Wireshark and used the code 
we've created in order to analyze our findings as listed below.

## conclusion
In this modern world, where the majority of the people uses IM apps in one way or another, 
trusting them with their out-most important information. These IM apps are far from perfect, 
we have shown in these project how vulnerable IM apps to analysis attacks, and how it is possible to aquire
private information whilst the victims are unaware of what happens.

## References

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Authers

For questions, feedback, or collaboration inquiries, reach out to Liel Yoash at [your@email.com].

Thank you for your interest in the IM App Traffic Analysis Project!
