Version: NAFATH-V3
Track: Networking

## Overview

A government AI assistant can help people find information about public services through a mobile app. It can answer common questions, explain how government services work, and guide users through the steps they need to follow. According to the OECD, artificial intelligence can help improve public services, make government work more efficient, and support better decisions. However, these benefits depend on how the system is developed and managed. Wrong answers and poor-quality data can confuse users and reduce their trust in the service. For this reason, the assistant should use reliable information, protect people's personal data, and explain clearly when it is not sure about an answer. Building a reliable assistant also requires different technical fields, including software, AI, mobile technology, networking, cybersecurity, and data management. Together, these fields can help make the service safer, more useful, and easier for citizens to use.

## Software

Software updates can change different parts of a program. For a government AI assistant, the MAJOR version increases when a change to the public API is not compatible with previous versions. The MINOR version increases when a new feature is added in a backward-compatible way. The PATCH version increases when a bug is fixed without changing the expected API behavior. These version numbers help developers understand the type of change made to the software.

Resource: Semantic Versioning 2.0.0 - https://semver.org/

## AI

Retrieval-Augmented Generation (RAG) searches relevant documents to help an AI assistant answer questions. The system uses the retrieved information to support its response instead of relying only on knowledge learned during training. In a government service app, RAG can help the assistant find relevant official service instructions before answering citizens. This can reduce incorrect answers, but it does not guarantee that every response will be accurate.

Resource: Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks - https://papers.nips.cc/paper/2020/hash/6b493230205f780e1bc26945df7481e5-Abstract.html

## Mobile

An iOS security feature called App Transport Security (ATS) helps protect data sent between an application and a server. It requires secure HTTPS connections when using the standard URL Loading System. iOS normally blocks plain HTTP connections through this system because they do not provide the required transport security, unless suitable exceptions are configured. Developers should use HTTPS to help protect citizens' data and keep connections secure in a government service app.

Resource: Preventing Insecure Network Connections - https://developer.apple.com/documentation/security/preventing-insecure-network-connections

## Networking

Devices on a network use IPv4 or IPv6 addresses to communicate. IPv4 uses 32-bit addresses, while IPv6 uses 128-bit addresses and provides a much larger number of available addresses. As more devices, including phones and smart devices, connect to the internet, the need for IP addresses grows. IPv6 supports this growth by providing many more addresses for connected devices. This can help a government AI assistant communicate with other systems as the number of connected devices increases.

Resource: RFC 8200 - Internet Protocol, Version 6 (IPv6) Specification - https://www.rfc-editor.org/rfc/rfc8200

## Cybersecurity

Prompt injection is a security risk that occurs when someone tries to change an AI assistant's behavior by giving it harmful instructions. Direct prompt injection comes from user input, while indirect prompt injection may come from external content, such as documents or websites. These attacks could cause a government AI assistant to provide incorrect answers or perform unsafe actions. To reduce the risk, developers should treat external content as untrusted and limit the assistant's access to sensitive information and actions.

Resource: LLM01: Prompt Injection - https://genai.owasp.org/llmrisk/llm01-prompt-injection/

## Data

Anonymization and pseudonymization are two methods of protecting personal information. Anonymization removes identifying information so that an individual cannot be identified using reasonably likely methods. Pseudonymization replaces identifying information with codes, although additional information may still link the data to an individual. Properly anonymized data falls outside the scope of the GDPR, while pseudonymized data generally remains personal data. This distinction is important when a government AI assistant handles citizens' data.

Resource: General Data Protection Regulation (GDPR) - https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32016R0679

## Misconception in My Track

## Open Question
