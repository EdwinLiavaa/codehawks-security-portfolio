# This is my Codehawks Security Portfolio
<p align="center">
 <img width="500" src="https://github.com/EdwinLiavaa/codehawks-security-portfolio/blob/main/logo.png">
</p>

## My Journey into Smart Contract Security Research: First Steps with Cyfrin Updraft

As I dive deeper into the world of blockchain security, I wanted to share my recent experience learning smart contract auditing through Cyfrin Updraft. The journey has been both challenging and rewarding, opening my eyes to the critical role security researchers play in the Web3 ecosystem.

## The Foundation: Understanding the Audit Process

One of the first crucial lessons I learned was the importance of proper protocol onboarding. It's not just about diving into code – a thorough understanding of the project's context is essential. Before even touching the codebase, we need to gather critical information about:

- Project overview and objectives
- Development environment and testing procedures
- Scope of the security review
- Chain compatibility and token specifications
- System roles and permissions
- Known issues and concerns

This systematic approach ensures we have all the necessary context to conduct a comprehensive security review.

## Tools of the Trade

I've been introduced to several powerful tools that are now essential parts of my security researcher toolkit:

- Solidity Metrics: For analyzing code complexity and interconnections
- CLOC: For measuring codebase size and scope
- Pandoc & LaTeX: For creating professional audit reports

These tools help quantify the work required for an audit and ensure our findings are presented professionally.

## The Audit Journey: A Structured Approach

I've learned that a successful audit follows distinct phases:

1. **Initial Review**
   - Scoping the protocol
   - Reconnaissance
   - Identifying vulnerabilities
   - Detailed reporting

2. **Protocol Fixes**
   - Working with developers on solutions
   - Ensuring proper test coverage

3. **Mitigation Review**
   - Verifying fixes
   - Final security assessment

## Real-World Experience: My First Security Review

The highlight of my training was conducting my first security review on the PasswordStore protocol. This hands-on experience helped me identify three distinct vulnerabilities:

- A critical access control issue in the `setPassword` function
- On-chain password storage privacy concerns
- Documentation inconsistencies in the `getPassword` function

This exercise taught me how to classify vulnerabilities using a severity matrix that considers both impact and likelihood. I learned that high-severity issues typically involve direct risk to funds or severe protocol disruption, while lower-severity findings might relate to code quality or documentation issues.

## Professional Development

Perhaps one of the most valuable skills I've developed is the ability to communicate findings professionally. I've learned to structure vulnerability reports with:

- Clear descriptions of the issue
- Detailed impact analysis
- Proof of Concept demonstrations
- Actionable mitigation recommendations

## Looking Ahead

This journey has shown me that smart contract security is not just about finding bugs – it's about understanding systems, thinking creatively about potential vulnerabilities, and communicating effectively with development teams.

The learning curve has been steep, but with each lesson and practical exercise, I'm building the skills needed to contribute meaningfully to blockchain security. I'm excited to continue this journey, tackle more complex protocols, and help make Web3 more secure for everyone.

As I progress in my security research career, I'll keep sharing my experiences and insights. Stay tuned for more updates on my journey in the fascinating world of smart contract security!

