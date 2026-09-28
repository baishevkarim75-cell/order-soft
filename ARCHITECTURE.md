# Public architecture

The showcase keeps implementation boundaries neutral:

- `MenuGateway` supplies demo menu data.
- `OrderGateway` represents a future order boundary; checkout is local demo behavior.
- `RecommendationProvider` represents product-level suggestions using demo rules.
- `Application Backend` and `Persistent Store` are documented concepts only.

No provider-specific AI, payment, restaurant, hosting or deployment implementation is included.
