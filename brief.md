Version: NAFATH-V3
Track: Networking

## Overview

A government AI assistant can help people find information about public services through a mobile app. It can answer common questions and guide users through the steps they need to follow. AI can help improve public services, but wrong answers and poor-quality data can confuse users and reduce their trust. The assistant should use reliable information, protect people's personal data, and explain when it is not sure about an answer. Building a reliable assistant requires software, AI, mobile technology, networking, cybersecurity, and data management. Networking is especially important because IPv4 and IPv6 provide addresses that help devices communicate as the number of connected devices grows.

## Software

Software updates can change different parts of a program. For a government AI assistant, the MAJOR version increases when a change to the public API is not compatible with previous versions. The MINOR version increases when a new feature is added in a backwards-compatible way. The PATCH version increases when a bug is fixed without changing the expected API behaviour. These version numbers help developers understand the type of change made to the software.

Resource: Semantic Versioning 2.0.0 - https://semver.org/

## AI

Retrieval-Augmented Generation (RAG) searches relevant documents to help an AI assistant answer questions. The system uses the retrieved information to support its response instead of relying only on knowledge learned during training. In a government service app, RAG can help the assistant find relevant official service instructions before answering citizens. This can reduce incorrect answers, but it does not guarantee that every response will be accurate.

Resource: Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks - https://papers.nips.cc/paper/2020/hash/6b493230205f780e1bc26945df7481e5-Abstract.html

## Mobile

An iOS security feature called App Transport Security (ATS) helps protect data sent between an application and a server. It requires secure HTTPS connections when using the standard URL Loading System. iOS normally blocks plain HTTP connections through this system because they do not provide the required transport security, unless suitable exceptions are configured. Developers should use HTTPS to help protect citizens' data and keep connections secure in a government service app.

Resource: Preventing Insecure Network Connections - https://developer.apple.com/documentation/security/preventing-insecure-network-connections

## Networking

Devices on a network use IPv4 or IPv6 addresses to communicate. IPv4 uses 32-bit addresses, while IPv6 uses 128-bit addresses and provides a much larger number of available addresses. As more devices, including phones and smart devices, connect to the internet, the need for IP addresses grows. IPv6 supports this growth by providing many more addresses for connected devices. This can help a government AI assistant communicate with other systems as the number of connected devices increases.

Resource: RFC 9386 - IPv6 Deployment Status - https://www.rfc-editor.org/rfc/rfc9386.html

## Cybersecurity

Prompt injection is a security risk that occurs when someone tries to change an AI assistant's behavior by giving it harmful instructions. Direct prompt injection comes from user input, while indirect prompt injection may come from external content, such as documents or websites. These attacks could cause a government AI assistant to provide incorrect answers or perform unsafe actions. To reduce the risk, developers should treat external content as untrusted and limit the assistant's access to sensitive information and actions.

Resource: LLM01: Prompt Injection - https://genai.owasp.org/llmrisk/llm01-prompt-injection/

## Data

Anonymization and pseudonymization are two methods of protecting personal information. Anonymization removes identifying information so that an individual cannot be identified using reasonably likely methods. Pseudonymization replaces identifying information with codes, although additional information may still link the data to an individual. Properly anonymized data falls outside the scope of the GDPR, while pseudonymized data generally remains personal data. This distinction is important when a government AI assistant handles citizens' data.

Resource: General Data Protection Regulation (GDPR) - https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32016R0679

## Misconception in My Track

A common misconception in networking is that IPv6 always provides faster internet than IPv4 because it is newer. However, IPv6 was mainly developed to provide more IP addresses as the number of connected devices grows. Using IPv6 does not automatically make an internet connection faster. Network congestion and connection quality are other factors that affect speed. IPv6 can support more connected devices for a government AI assistant, but it does not guarantee faster service.

## Open Question

How can network engineers use IPv6 and other technologies to support more devices, reduce congestion, and maintain reliable access to government services as more citizens use an AI assistant? What challenges may arise when moving from IPv4 to IPv6, and how can they be addressed?
