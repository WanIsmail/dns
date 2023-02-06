How to protect domains that do not send emails

https://www.cloudflare.com/learning/dns/dns-records/protect-domains-without-email/


What are the different types of DNS TXT records used for email authentication?

There are three main types of DNS TXT records used for email authentication. Each of them differs slightly in how they work:

Sender Policy Framework (SPF) records list all of the IP addresses and domain names that are authorized to send emails on behalf of the domain.
DomainKeys Identified Mail (DKIM) records provide a digital signature to authenticate whether or not the sender actually authorized the email. This digital signature also helps prevent on-path attacks, in which attackers intercept communications and alter messages for nefarious purposes.
Domain-based Message Authentication, Reporting and Conformance (DMARC) records hold a domain’s DMARC policy. DMARC is a system for authenticating emails by checking a domain’s SPF and DKIM records. The DMARC policy states whether emails that fail SPF or DKIM checks should be marked as spam, blocked, or allowed to go through.
