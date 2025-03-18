# AI-Based-Network-Reconnaissance-Tool-for-Network-Security-Administrators

## Overview
The AI-Based Network Reconnaissance Tool combines AI (GPT-3/4) with Nmap to provide Network Security Administrators, Penetration Testers, and SOC Analysts with a solution for network reconnaissance. This tool converts natural language inputs into network scanning commands which makes the scanning process efficient and straightforward.

The actual Documentation is only available upon request, which concerns the indepth research and the metrics used in training the model. 

## Features
- **Natural Language Command Processing**: Users enter scan requests through text input or voice recognition. The AI model interprets these inputs and generates appropriate Nmap commands.
- **Interactive Command Review**: Users can accept, modify, or cancel generated commands before execution.
- **Fast Processing**: Nmap runs on an Amazon EC2 instance, ensuring rapid command execution.
- **User-Friendly Interface**: A chat interface built with Next.js and modern web technologies.
- **Downloadable Results**: Users can view results in Markdown format or download them as PDF files.
- **Sidebar Functionalities**:
  - History
  - Documentation
  - Feedback
  - Text Input Samples

## Technology Stack
- **Frontend**: Next.js, Tailwind CSS, Vercel (for serverless hosting)
- **Backend**: Nmap hosted on Amazon EC2 Linux environment
- **AI Model**: GPT-3/4 (Fine-tuned to generate network scanning commands)
- **Communication**: API key-based interaction between the Vercel application and EC2 instance

## How It Works
1. **Input Handling**:
   - Users enter scan requests via text or voice input.
   - AI processes the request and generates an Nmap command.
2. **Command Review**:
   - Users can accept, modify, or cancel the command before execution.
3. **Scan Execution**:
   - Approved commands are sent to the Nmap server hosted on EC2 for processing.
4. **Result Display**:
   - Results are provided in a user-friendly format with options for PDF download and Markdown rendering.

## Example Queries
- "Scan my website umat.edu.gh for vulnerabilities on the first 100 ports."
- "Perform an aggressive scan to find everything on this server 8.8.8.8."
- "Find any SSH servers running older versions on 8.8.8.8."
- "What open ports are available on this IP 8.8.8.8."

## Safety and Ethical Use
Ensure you have permission to scan networks or hosts. Unauthorized scanning may be illegal in some jurisdictions.


## You stand to Get an Attacker perspective of the Results and the NetworkAdministrator Perspective of the results - this is the Interpretations part - Awesome ritght?

## Future Plans

Artificial Intelligence presents an opportunity to enhance traditional systems by automating tasks and reducing learning difficulties. This project aims to achieve these improvements through several key areas:

- **Improved AI Training**: Enhancing the AI model to generate more effective Nmap commands for complex network scanning requests.

- **Multi-Tool Support**: Extending compatibility to include other network security tools beyond Nmap.

- **Real-Time Feedback**: Providing immediate updates during scans, alongside the timed process indicator.

- **More Output Formats**: Introducing additional export options such as JSON, XML, and expanded functionalities.

- **User Authentication & Rate Limiting**: Implementing robust access control to improve security.

Future updates will also focus on integrating reinforcement learning to enable the tool to adapt dynamically when performing scans. For example, if a scan doesn't produce results, the tool will automatically adjust its approach and inform users of the initial attempt’s outcome, continuing until substantial results are achieved. This improvement aims to make the tool more reliable and efficient for network reconnaissance.

Currently, the application is hosted on the Vercel platform. Due to potential Amazon EC2 charges, the Nmap functionality is disabled until further development. However, the project demonstrates significant potential for expanding AI applications in cybersecurity. As seen in the military’s use of AI for advanced operations, the same approach can benefit blue teamers and security professionals by enhancing detection and mitigation capabilities.

You can still access the live project via the link: https://recon-nydl.vercel.app
signup and have a feel of it. Share and Provide feedback as well.
