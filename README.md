# secbyte-api-security-jwt-graphql-rest-hardening-ctf-labs
A practical collection of cybersecurity CTF labs covering API security testing &amp; hardening (REST API broken authorization, JWT token forgery &amp; signature manipulation, GraphQL introspection abuse &amp; query shaping, rate-limiting bypasses, API injection flaws, and input validation defenses).
# API Security Testing, JWT Token Forgery, GraphQL Introspection & REST API Hardening CTF Labs

Welcome to the **API Security Testing, JWT Token Forgery, GraphQL Introspection & REST API Hardening CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on API application security (OWASP API Security Top 10), token authentication mechanics, and input validation defenses—spanning **API Fundamentals & Discovery (Request structures, endpoint discovery, secure exploitation baselines)**, **Input Validation & Secure Coding (Input sanitization, parameter tampering, secure coding pipelines)**, **API Authentication, Authorization & JWT Attacks (JWT signature bypass, token forgery, BOLA/BOPA broken boundaries, API trust boundaries)**, **GraphQL Security & Query Abuse (Introspection query mapping, query depth/cost attacks, circular relation exploitation)**, and **REST API Hardening & Abuse Defenses (Rate limiting bypasses, inventory API defenses, business logic abuse mitigation)**.

---

## Lab Collection Index

### 1. API Security Fundamentals & Input Validation Defenses
* **API Fundamentals: From Requests to Secure Exploitation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/api-fundamentals-from-requests-to-secure-exploitation](https://learn.secbyte.org/ctf/api-fundamentals-from-requests-to-secure-exploitation)  
  *Focus:* Understanding RESTful API request structures, inspecting HTTP methods (`GET`, `POST`, `PUT`, `PATCH`, `DELETE`), analyzing JSON/XML payload syntaxes, and identifying raw API endpoints.

* **Input Validation: From Trust to Tamper**  
  *Lab Link:* [https://learn.secbyte.org/ctf/input-validation-from-trust-to-tamper](https://learn.secbyte.org/ctf/input-validation-from-trust-to-tamper)  
  *Focus:* Bypassing weak client-side input validation controls, tampering with JSON payload parameters, evaluating server-side sanitization routines, and enforcing strict schema validation.

* **Secure Coding Fundamentals: From Input to Incident**  
  *Lab Link:* [https://learn.secbyte.org/ctf/secure-coding-fundamentals-from-input-to-incident](https://learn.secbyte.org/ctf/secure-coding-fundamentals-from-input-to-incident)  
  *Focus:* Establishing secure software development principles for API endpoints—implementing allow-list input validation, preventing unhandled exceptions, and securing data serialization flows.

* **API Injection Attacks: From Input Abuse to Exploitation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/api-injection-attacks-from-input-abuse-to-exploitation](https://learn.secbyte.org/ctf/api-injection-attacks-from-input-abuse-to-exploitation)  
  *Focus:* Exploiting server-side injection vulnerabilities in API endpoints—SQL injection (SQLi), NoSQL injection (MongoDB operators), and Command Injection via JSON/XML parameters.

### 2. API Authentication, JWT Security & Authorization Testing
* **API Authentication: From Tokens to Trust Boundaries**  
  *Lab Link:* [https://learn.secbyte.org/ctf/api-authentication-from-tokens-to-trust-boundaries](https://learn.secbyte.org/ctf/api-authentication-from-tokens-to-trust-boundaries)  
  *Focus:* Auditing token-based authentication systems, identifying weak API key implementations, evaluating OAuth 2.0 bearer token flows, and mapping backend microservice trust boundaries.

* **JWT Security: From Decoding to Token Forgery**  
  *Lab Link:* [https://learn.secbyte.org/ctf/jwt-security-from-decoding-to-token-forgery](https://learn.secbyte.org/ctf/jwt-security-from-decoding-to-token-forgery)  
  *Focus:* Exploiting JSON Web Token (JWT) implementation flaws—algorithm confusion attacks (`alg: none`, HMAC vs. RSA), brute-forcing weak HMAC secret keys, manipulating claim payloads, and forging valid administrative tokens.

<Image src="image_agent_tag_7162713559039842011" alt="JWT API gateway security architecture diagram showing token validation flow" caption="JWT API Gateway Authentication & Security Architecture" />

---

* **API Authorization Testing: Broken Boundaries**  
  *Lab Link:* [https://learn.secbyte.org/ctf/api-authorization-testing-broken-boundaries](https://learn.secbyte.org/ctf/api-authorization-testing-broken-boundaries)  
  *Focus:* Testing for Broken Object Level Authorization (BOLA / IDOR) and Broken Object Property Level Authorization (BOPA)—manipulating object IDs in resource endpoints to access unauthorized user data.

* **API Security Testing: From Discovery to Broken Authorization**  
  *Lab Link:* [https://learn.secbyte.org/ctf/api-security-testing-from-discovery-to-broken-authorization](https://learn.secbyte.org/ctf/api-security-testing-from-discovery-to-broken-authorization)  
  *Focus:* Conducting end-to-end API penetration tests—discovering shadow/undocumented API endpoints via OpenAPI/Swagger spec parsing, and identifying privilege escalation flaws.

### 3. GraphQL Security & Query Abuse
* **GraphQL Security: Query Shaping, Introspection & Abuse Prevention**  
  *Lab Link:* [https://learn.secbyte.org/ctf/graphql-security-query-shaping-introspection-abuse-preventio](https://learn.secbyte.org/ctf/graphql-security-query-shaping-introspection-abuse-preventio)  
  *Focus:* Analyzing GraphQL API attack surfaces—leveraging introspection queries to extract full database schemas, executing query batching attacks, exploiting circular relation queries for Denial of Service (DoS), and hardening GraphQL resolvers.

<Image src="image_agent_tag_7162713559039842328" alt="GraphQL introspection query schema mapping visualization diagram" caption="GraphQL Introspection Query Schema Mapping & Attack Surface" />

---

### 4. REST API Hardening, Rate Limiting & Business Logic Protection
* **REST API Security: From Broken Auth to Business Logic Abuse**  
  *Lab Link:* [https://learn.secbyte.org/ctf/rest-api-security-from-broken-auth-to-business-logic-abuse](https://learn.secbyte.org/ctf/rest-api-security-from-broken-auth-to-business-logic-abuse)  
  *Focus:* Identifying complex business logic flaws in REST APIs—mass assignment vulnerabilities, race conditions during checkout/transfer workflows, and improper multi-step process enforcement.

* **API Rate Limiting: Bypass, Abuse, Defend**  
  *Lab Link:* [https://learn.secbyte.org/ctf/api-rate-limiting-bypass-abuse-defend](https://learn.secbyte.org/ctf/api-rate-limiting-bypass-abuse-defend)  
  *Focus:* Bypassing API rate-limiting and throttling controls using IP rotation (`X-Forwarded-For` header spoofing), path case variations, and request batching; and implementing robust API gateway rate limits.

* **API Hardening: Defend the Broken Inventory API**  
  *Lab Link:* [https://learn.secbyte.org/ctf/api-hardening-defend-the-broken-inventory-api](https://learn.secbyte.org/ctf/api-hardening-defend-the-broken-inventory-api)  
  *Focus:* Hardening vulnerable legacy microservice APIs—enforcing strict CORS policies, restricting HTTP methods, enforcing field-level property authorization, and deprecating improper API inventory endpoints (Improper Assets Management).

---

## Learning Path

### Path A: API Penetration Tester & Security Auditor
1. **API Discovery & Basics:** Start with [API Fundamentals](https://learn.secbyte.org/ctf/api-fundamentals-from-requests-to-secure-exploitation) and [API Security Testing](https://learn.secbyte.org/ctf/api-security-testing-from-discovery-to-broken-authorization).
2. **Auth & Token Exploitation:** Master attack vectors in [API Authentication](https://learn.secbyte.org/ctf/api-authentication-from-tokens-to-trust-boundaries), [JWT Security](https://learn.secbyte.org/ctf/jwt-security-from-decoding-to-token-forgery), and [API Authorization Testing](https://learn.secbyte.org/ctf/api-authorization-testing-broken-boundaries).

### Path B: GraphQL & Advanced API Attack Specialist
1. **GraphQL Schema & Queries:** Audit GraphQL environments in [GraphQL Security](https://learn.secbyte.org/ctf/graphql-security-query-shaping-introspection-abuse-preventio).
2. **Injections & Logic Abuse:** Exploit input flaws in [API Injection Attacks](https://learn.secbyte.org/ctf/api-injection-attacks-from-input-abuse-to-exploitation) and [REST API Security](https://learn.secbyte.org/ctf/rest-api-security-from-broken-auth-to-business-logic-abuse).

### Path C: AppSec Engineer & API Hardening Developer
1. **Validation & Secure Coding:** Secure application code in [Input Validation](https://learn.secbyte.org/ctf/input-validation-from-trust-to-tamper) and [Secure Coding Fundamentals](https://learn.secbyte.org/ctf/secure-coding-fundamentals-from-input-to-incident).
2. **Gateway Hardening & Throttling:** Protect infrastructure via [API Rate Limiting](https://learn.secbyte.org/ctf/api-rate-limiting-bypass-abuse-defend) and [API Hardening](https://learn.secbyte.org/ctf/api-hardening-defend-the-broken-inventory-api).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the direct link to launch the exercise environment hosted on Learn SecByte.
3. Review scenario directives, Postman/Insomnia collection files, OpenAPI specification docs, JWT tokens, or GraphQL endpoint URLs.
4. Intercept API requests using Burp Suite, forge signed JWT tokens, execute GraphQL schema introspection queries, manipulate parameter IDs to bypass authorization (BOLA), or bypass gateway rate-limiting headers to capture flags.

---

## Target Audience

* **Application Security (AppSec) Engineers:** Enforce OWASP API Security Top 10 defenses, implement API gateway security policies, and conduct GraphQL/REST code reviews.
* **Penetration Testers & Security Auditors:** Execute API penetration tests, exploit JWT implementation bugs, bypass rate limits, and audit BOLA/BOPA authorization boundaries.
* **Backend Developers & Software Architects:** Build secure REST/GraphQL endpoints, enforce schema-level input validation, implement secure JWT signature verification, and mitigate mass assignment bugs.
* **Cybersecurity Students:** Acquire practical hands-on experience in modern microservice security, REST/GraphQL protocol mechanics, and token security analysis.

---

## Disclaimer

All lab links provided in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Executing unauthorized API scanning, token forgery, or rate-limit abuse against external production APIs is strictly prohibited.
