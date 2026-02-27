# Stripe Go-Live Checklist

## Required from Owner
- Restricted secret key
- Publishable key
- Webhook signing secret (after endpoint created)
- Support email
- Refund policy selection

## Stripe Setup Steps
1. Create products + prices:
   - OpenClaw Starter Kit ($29)
   - Claude Code Solo Builder Kit ($29)
   - Security Guardrails Pack ($24)
2. Generate Payment Links (phase 1 fastest)
3. Add success URL: `https://launchmyagent.live/thank-you`
4. Add cancel URL: `https://launchmyagent.live/products`
5. Configure webhook endpoint:
   - event: `checkout.session.completed`
6. Delivery action:
   - send product access link and receipt instructions

## Safety
- Use restricted API keys only
- Do not store live secrets in repo files
- Rotate keys after initial launch if shared temporarily
