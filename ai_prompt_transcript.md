# Reconstructed AI Prompt Record

This record was reconstructed from the recommendations used to complete `student_plan.json`; it is not represented as a verbatim export of the original chat. Each prompt follows the template supplied in the student activity.

## UC1 Quick read-only API exploration

### Prompt

> I am selecting a Cisco DevNet resource for a fictional classroom use case.  
> Use case: A student team needs immediate access to a shared Cisco environment to practice safe read-only API requests. Administrative changes are not required, and the team cannot wait for provisioning.  
> Choose exactly one: learning-lab, always-on-sandbox, reservation-sandbox, or code-exchange.  
> Explain which requirement drove your choice. State any access, isolation, setup, or privilege claim that I should verify in official Cisco documentation.  
> Do not invent a sandbox product name, URL, account, or credential.

### AI response

I recommend `always-on-sandbox`. The decisive requirement is immediate access to a shared environment for non-administrative API practice without waiting for provisioning. Verify in Cisco's official DevNet Sandbox documentation that Always-On environments require no reservation or setup time, are shared, and restrict administrative access.

## UC2 Private configuration testing

### Prompt

> I am selecting a Cisco DevNet resource for a fictional classroom use case.  
> Use case: A development team must test configuration changes with administrative access in a private environment. The team can schedule access, use a VPN, and accept setup time.  
> Choose exactly one: learning-lab, always-on-sandbox, reservation-sandbox, or code-exchange.  
> Explain which requirement drove your choice. State any access, isolation, setup, or privilege claim that I should verify in official Cisco documentation.  
> Do not invent a sandbox product name, URL, account, or credential.

### AI response

I recommend `reservation-sandbox`. The decisive requirements are private access and administrative control for configuration testing. Verify in Cisco's official DevNet Sandbox documentation that Reservation Sandboxes are private, provide administrative access, require a reservation and setup time, and commonly require a VPN connection.

## UC3 Guided API concept practice

### Prompt

> I am selecting a Cisco DevNet resource for a fictional classroom use case.  
> Use case: A beginner needs structured, step-by-step learning content before attempting an independent API activity. The immediate goal is guided practice rather than access to administrative devices.  
> Choose exactly one: learning-lab, always-on-sandbox, reservation-sandbox, or code-exchange.  
> Explain which requirement drove your choice. State any access, isolation, setup, or privilege claim that I should verify in official Cisco documentation.  
> Do not invent a sandbox product name, URL, account, or credential.

### AI response

I recommend `learning-lab`. The decisive requirement is structured, step-by-step instruction for a beginner before independent API work. Verify on Cisco DevNet Learning that it provides organized learning content and labs; also confirm that the use case does not require private administrative access or a reserved execution environment.

## UC4 Reusable automation example

### Prompt

> I am selecting a Cisco DevNet resource for a fictional classroom use case.  
> Use case: A developer wants to examine community and Cisco-maintained code repositories for an existing network-automation use case before designing a new solution.  
> Choose exactly one: learning-lab, always-on-sandbox, reservation-sandbox, or code-exchange.  
> Explain which requirement drove your choice. State any access, isolation, setup, or privilege claim that I should verify in official Cisco documentation.  
> Do not invent a sandbox product name, URL, account, or credential.

### AI response

I recommend `code-exchange`. The decisive requirement is finding existing Cisco and community code repositories and reusable network-automation examples. Verify on the official Cisco Code Exchange pages that the service provides a curated, searchable collection of code repositories and automation use cases; any selected code must still be reviewed and tested for the intended use.
