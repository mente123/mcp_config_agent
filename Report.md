// Technical Report
--> I updated the copilot-instructions.md filr to include some additional logic, on top of calling the mcp server tools before every response, I integrated rules that require the Agent to provide technical plan and wait for my approval before it modifies any code.

--> Forcing a <plan> block gave me a chance to see what the AI intended to do, preventing accidental changes in VS code.

--> Initially the AI tried to create files at the same time it was logging, I had to add a stop rule to forbid file creation until I say proceed.

--> I faced a challange when pushing to my repo because of the token and generated a new token.

--> I learned that rules are almost the powerful way to align an AI agent with my intention to do something, without the rules, the Agent tries to give a response as soon as possible whih will cause hallucination and even wrong answer and unfortunately it will give you the answer confidently. So the rules are necessary which is first log, then plan for the prompt, then approve from the developer if that plan aligns with the developer idea and finally execute.

Some Screenshot throughout the process
![alt text](<Screenshot 2026-02-02 at 3.18.05 PM.png>) ![alt text](<Screenshot 2026-02-02 at 3.18.01 PM.png>) ![alt text](<Screenshot 2026-02-02 at 3.17.53 PM.png>) ![alt text](<Screenshot 2026-02-02 at 3.17.48 PM.png>) ![alt text](<Screenshot 2026-02-02 at 2.42.09 PM.png>)
