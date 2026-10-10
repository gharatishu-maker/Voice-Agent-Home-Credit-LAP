# Voice-Agent-Home-Credit-LAP
This project is a voice-based AI agent built using Retell AI to simulate a customer conversation for a Home Credit Loan Against Property (LAP) offer.
The agent, named Cimo, speaks in English and guides customers through an initial eligibility assessment. It asks relevant questions, collects property and financial details, checks eligibility rules, and explains the next steps to eligible customers.
This is an educational demonstration. It is not an official Home Credit service and does not approve loans or provide financial advice.

Objectives
Build an AI voice agent using Retell AI.
Simulate a natural customer conversation in English.
Collect the information required for an initial LAP eligibility assessment.
Apply eligibility rules consistently.
Handle ineligible customers and existing loan-transfer requests appropriately.
Test the agent using a simulated conversation and review its transcript.
Tools and Technologies
Retell AI – Voice agent creation and conversation testing.
Large Language Model (LLM) – Natural-language conversation and instruction following.
GitHub – Project documentation and version control.

Key Features
1. Customer Introduction and Verification
The agent introduces itself and checks that it is speaking to the intended customer before discussing offer details.
2. Loan Offer Explanation
The agent explains the simulated offer of a Loan Against Property of up to ₹75,00,000, subject to eligibility.
3. Eligibility Assessment
The agent collects the following seven details:
Property type: Residential, Commercial, or Industrial properties are eligible for further assessment. Agricultural property is disqualified.
Ownership: Sole and Joint ownership are accepted.
Original property documents: The customer must have the original documents available.
Requested loan amount: The maximum offer amount is ₹75,00,000.
Occupation and income method: The customer must be Salaried or Self-employed, with income received through a bank. Cash-only income is disqualified.
Property market value: The agent records the customer's estimated current property value without inventing a minimum threshold.
Loan tenure: The requested tenure must be between 3 and 15 years, inclusive.
4. Disqualification Handling
If a mandatory eligibility condition fails, the agent explains the reason politely and ends the conversation.
5. Existing Loan Transfer Requests
If a customer wants to transfer an existing Loan Against Property or reduce their EMI, the agent explains that a loan-transfer specialist will contact them.
6. Successful Initial Qualification
When all seven details are collected and the initial eligibility conditions are met, the agent summarizes the customer's answers and explains that a senior loan expert will discuss the next steps and exact interest rate.

The agent does not guarantee loan approval or invent an interest rate.

*Conversation Workflow*
Introduce the agent.
Verify the customer's identity.
Explain the LAP offer.
Collect the seven eligibility details.
Check eligibility and handle disqualification when applicable.
Summarize the customer's information.
Explain the next steps and close the conversation politely.
The agent is instructed to remember details already provided, avoid unnecessarily repeating questions, and respond naturally to customer interruptions or corrections.

Testing
The agent was tested using Retell AI's audio testing interface with fictional customer details.
The successful test scenario included:
Residential property.
Sole ownership.
Original property documents available.
Requested loan amount of ₹10 lakh.
Salaried employment.
Salary credited to a bank account.
Estimated property market value of ₹15 lakh.
Requested tenure of five years.
The agent collected the required details, summarized the answers, and explained that a senior loan expert would follow up.


Project Files
The repository can contain the following files:
home-credit-lap-voice-agent/
├── README.md
├── system_prompt.txt
└── test_transcript.txt


Submission Links
Published Retell AI Agent: https://agent.retellai.com/orb/agent_467cc3b2e76741f3d70b06fa35?token=3f8c56c1220cb121174866c4e917be3a
