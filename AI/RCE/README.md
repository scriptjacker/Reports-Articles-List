1. Shelltorch CVE-2023-43654 in Torchserve via SSRF in Pytorch in LLMs - https://www.oligo.security/blog/shelltorch-explained-multiple-vulnerabilities-in-pytorch-model-server#the-story-behind-shelltorch (Exploit - https://github.com/OligoCyberSecurity/CVE-2023-43654)

2. Direct Prompt Injection CVE-2024-5565 leads RCE - https://jfrog.com/blog/prompt-injection-attack-code-execution-in-vanna-ai-cve-2024-5565/ (good analysis about function calling, SQL queries, methodology to understand how to build prompt)

3. Prompt Injection and trying it bypasses i.e Base 64 and analysing the request leads to execute system commands and python code - https://www.blazeinfosec.com/post/llm-pentest-agent-hacking/ (In response of AI it was not executing the paylaod, however in knowledge parameter in response in burp)

4. Prompt Injection & ASCII smuggling (CVE-2025-53773) leads RCE - https://embracethered.com/blog/posts/2025/github-copilot-remote-code-execution-via-prompt-injection/ (Also confused deputy kind of and via vulnerable MCP)
