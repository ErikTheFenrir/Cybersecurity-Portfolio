# Incident Handler Journal

## Entry #1: Wireshark Analysis (2026-02-05)

2026-02-05	Entry: #1
Description	Analyserade PCAP fil i Wireshark för misstänkt nätverkstrafik till en webbplats, filtrerade även protokoll och undersökte packet strukturer.
Tool(s) used Wireshark(analyserade med filter som “tcp.port == 80”, “curl”, “dns”

The 5 W's Capture the 5 W's of an incident.
● Who: Användare som körde curl mot extern site (potentiell C2). ● What: Web-förfrågningar och DNS-queries i TCP/UDP med HTTP-payload. 
● When: Under capture-perioden 2022-11-23. 
● Where: Nätverksgränssnitt i Coursera-labbmiljö. 
● Why: Insider-åtkomst eller bristande endpoint-filtrering.

Additional notes: Använde mig av coloring rules för att snabbt visuellt kunna urskilja olika segment. 
IP adresser är anonymiserade med blåa rutor.
