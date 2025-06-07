# Email Service Project

A mock email service that includes:
- Retry with exponential backoff
- Provider fallback
- Idempotency
- Rate limiting
- Status tracking
- Circuit breaker
- Simple logging and queue

## Commands

```bash
npm install
npm run build
npm run test
```

## Structure
- `src/EmailService.ts` - Core logic
- `src/providers/MockProviderA.ts` - Mock provider A
- `src/providers/MockProviderB.ts` - Mock provider B
- `src/utils/*` - Helper utils (circuit breaker, rate limiter, logger)
- `tests/` - Unit tests