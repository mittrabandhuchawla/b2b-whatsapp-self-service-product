
# Customer Journey: Conversational Product Ordering

## Scenario

An existing B2B customer wants to purchase electrical products using WhatsApp without knowing the exact product SKU.

This is an illustrative journey for the proposed product evolution, not a screenshot or transcript of a deployed experience.

## User Journey

| Stage | Customer Action | System Response |
|---|---|---|
| 1. Entry | Opens WhatsApp conversation | Offers assistance |
| 2. Identification | Starts product inquiry | Identifies permitted customer context |
| 3. Search | Describes required products | Interprets specifications and searches approved catalog |
| 4. Clarification | Answers missing product details | Narrows down matching items |
| 5. Selection | Selects products | Builds structured basket |
| 6. Review | Checks products and quantities | Displays basket summary |
| 7. Commercial Check | Requests order submission | Retrieves applicable terms from approved systems |
| 8. Confirmation | Explicitly confirms | Submits order request |
| 9. Acknowledgement | Receives submission status | Explains next step and confirmation status |

## Illustrative Conversation

**Customer:** I need 10 pieces of a 16A single-pole MCB.

**Assistant:** I can help you find a matching product. Do you have a preferred brand?

**Customer:** Brand A.

**Assistant:** I found a possible match in the approved catalog. Please confirm the product specifications.

**Customer:** Yes.

**Assistant:** Would you like to add 10 units to your basket?

**Customer:** Yes.

**Assistant:** Your basket contains 10 units. Please review the order details and applicable commercial information before submitting.

**Customer:** Submit order.

**Assistant:** Your order request has been submitted. Final acceptance is subject to the applicable business checks.

## Exception Scenarios

### Ambiguous Product

If specifications are incomplete, request clarification before suggesting a product.

### Product Not Found

Avoid inventing a SKU. Offer an inquiry or human assistance.

### Customer Not Verified

Do not reveal account-specific prices or documents before authorization requirements are satisfied.

### Backend Unavailable

Explain that the request cannot currently be completed and offer an approved fallback route.

### Commercial Check Failed

Do not promise order acceptance. Explain the available next steps.

## Product Design Principles

1. Minimize unnecessary customer steps.
2. Support natural language without losing accuracy.
3. Keep important commercial decisions deterministic.
4. Confirm the customer's intention before transactions.
5. Make failures understandable and recoverable.
6. Provide a clear human handoff when required.

## Portfolio Note

This journey is a generalized proposed design. The conversation uses fictional product details and is not a production interaction.

