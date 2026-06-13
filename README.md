# Instamojo

Indian digital payments and e-commerce platform with a REST API for payment requests, refunds, store products, order management, and mobile payment links. Trusted by over 1.2 million Indian small businesses.

## Links

- [Website](https://www.instamojo.com/)
- [Documentation](https://docs.instamojo.com/)
- [GitHub Organization](https://github.com/Instamojo)
- [Blog](https://www.instamojo.com/blog/)
- [Pricing](https://www.instamojo.com/pricing/)
- [LinkedIn](https://www.linkedin.com/company/instamojo)
- [X / Twitter](https://twitter.com/instamojo)

## API

The Instamojo Payments API is a REST API with base URL `https://api.instamojo.com/v2/`. It uses Application-Based Authentication with Bearer tokens. Key endpoints include:

- `POST /generate-access-token-application-based-authentication` - Generate access token
- `POST /payment_requests/` - Create a payment request
- `GET /payment_requests/{id}/` - Get a payment request
- `POST /payment_requests/{id}/orders/` - Create an order from a payment request
- `GET /payments/{id}/` - Get payment details
- `POST /refunds/` - Create a refund
- `GET /refunds/{id}/` - Get refund details

## Pricing

Instamojo charges per-transaction fees rather than API call fees:

- **Free plans**: 5% + ₹3 per transaction
- **Paid plans**: 2% + ₹3 per transaction
- **Corporate cards**: 3% + ₹3 per transaction
- 18% GST applies to all transaction fees

## Maintainers

- Kin Lane (kin@apievangelist.com)
