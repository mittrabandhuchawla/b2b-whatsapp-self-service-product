
# Product Brief

## Product

B2B WhatsApp Customer Self-Service and Conversational Commerce Assistant

## Product Category

Conversational Commerce / Business Process Automation / B2B Customer Experience

## 1. Problem Statement

B2B distribution customers frequently rely on sales and support teams for routine information, documentation and product inquiries.

Many business customers already use WhatsApp as a convenient communication channel.

A structured self-service assistant can reduce the need to contact internal teams for every request. However, a menu-driven experience may still require customers to understand predefined options or product terminology.

The product opportunity is to make business interactions more intuitive while maintaining operational reliability and appropriate commercial controls.

## 2. Target Users

### Existing B2B Customers

Customers who need account information, commercial documents, product information or ordering assistance.

### New Business Prospects

Businesses seeking product information, quotations or a new trading relationship.

### Dormant Customers

Previously active customers who may benefit from re-engagement and assistance.

### Sales and Support Teams

Internal users who handle inquiries, requests, commercial exceptions and customer follow-ups.

## 3. Product Objectives

### Objective 1: Simplify Customer Self-Service

Allow customers to access routine information and initiate service requests through WhatsApp.

### Objective 2: Improve Product Discovery

Enable customers to describe product requirements using familiar terminology, rather than requiring exact product codes.

### Objective 3: Enable Conversational Commerce

Design a guided order journey covering product selection, quantity confirmation, basket review and order submission.

### Objective 4: Support Business Controls

Ensure that customer-specific information, commercial decisions and order eligibility remain controlled by approved backend systems.

## 4. Proposed MVP Scope

- Customer identification and classification
- Natural-language product requirement interpretation
- Product matching against an approved catalog
- Clarification for ambiguous requirements
- Basket review and modification
- Order submission with explicit confirmation
- Order acknowledgement
- Escalation when automated processing is insufficient

Existing self-service functions should be preserved where technically and operationally appropriate.

## 5. Functional Requirements

**FR-01: Customer Identification**  
The system should identify the customer context before exposing account-specific information.

**FR-02: Product Search**  
The user should be able to describe products using natural language.

**FR-03: Catalog-Grounded Results**  
Product suggestions should reference approved catalog records.

**FR-04: Ambiguity Handling**  
The system should ask clarifying questions when it cannot confidently identify a product.

**FR-05: Basket Management**  
The customer should be able to review and adjust product quantities.

**FR-06: Commercial Information**  
Applicable prices and commercial eligibility should be obtained from authorized systems.

**FR-07: Order Confirmation**  
The customer should explicitly confirm their order before submission.

**FR-08: Order Status**  
The system should distinguish between an order request being submitted and the order being commercially accepted.

**FR-09: Human Escalation**  
Unresolved requests should be routed to an appropriate team.

## 6. Non-Functional Considerations

- Privacy and access control
- Reliability of system integrations
- Understandable error handling
- Auditability of important transactions
- Multilingual usability
- Availability of fallback workflows
- Maintainability of existing integrations

## 7. Key Dependencies

- Accurate and structured product catalog
- Customer identification and account-mapping capability
- Approved pricing and commercial rules
- Order-processing services
- WhatsApp platform availability
- Operational ownership of customer escalations
- Product and business stakeholder alignment

## 8. Scope Boundaries

The proposed product does not independently authorize credit, set final commercial prices, approve new trading accounts or guarantee stock availability.

These decisions remain subject to approved business processes and authoritative systems.

## 9. Product Management Perspective

A successful experience must balance simplicity for customers with accuracy, control and operational feasibility.

The desired outcome is not automation for its own sake, but a more convenient customer journey that can be implemented and maintained responsibly.

---

*This document is a sanitized, generalized portfolio artifact based on a real product requirements initiative. It does not represent an approved public specification or a completed product release.*
