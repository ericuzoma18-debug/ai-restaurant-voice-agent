# AI Restaurant Voice Agent — Mama Tee’s Kitchen

An AI-powered restaurant voice agent built to handle customer calls, answer enquiries, and support order and reservation workflows.

## Project Overview

Restaurants receive repetitive calls about menus, prices, orders, reservations, and delivery. This project explores how an AI voice agent can handle these interactions conversationally while automating the collection of customer and order information.

## How It Works

1. A customer calls and interacts with the AI voice agent.
2. The agent answers questions about the restaurant, menu, prices, delivery, and reservations using its configured instructions.
3. When appropriate, the agent uses a Vapi API request tool to send order or reservation information to an n8n webhook.
4. n8n processes the incoming data and appends the relevant order information to Google Sheets.
5. The restaurant team can review the captured information and follow up.

## Key Features

- AI-powered voice conversations
- Restaurant enquiry handling
- Order information collection
- Delivery and pickup information capture
- Reservation-related interactions
- Automated data transfer through a webhook
- Google Sheets order records

## Technologies Used

- **Vapi** — Voice agent and tool configuration
- **Twilio** — Phone integration
- **OpenAI** — Conversational AI
- **n8n** — Workflow automation and webhook processing
- **Google Sheets** — Order data storage

## Project Screenshots


## Project Demo

**Demo video:** (https://lnkd.in/p/eG2fmgvE)

## Business Value

This project demonstrates how voice AI and workflow automation can help restaurants manage repetitive customer enquiries and reduce manual order-recording work.

## Future Improvements

- More complete reservation management
- Order confirmation notifications
- Integration with restaurant ordering systems
- CRM integration and customer follow-up

## Disclaimer

This is a portfolio demonstration. Features and integrations should be tested against the restaurant's operational requirements before production deployment.
