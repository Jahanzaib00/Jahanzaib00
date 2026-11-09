## Jahanzaib Khursheed

**I work on systems where mistakes are expensive.**

Payment flows, idempotent APIs, document pipelines that feed government processes, protocol
servers that talk to physical hardware — and the infrastructure underneath them. Mostly
TypeScript and Python, mostly NestJS, React/React Native and AWS, usually as the engineer who
owns the thing end to end: schema, API, client, pipeline, deploy.

BS Computer Science, Lahore University of Management Sciences (LUMS). Software Engineer II.
Based in Lahore, Pakistan.

---

### Selected work

Almost all of it is private or under client NDA, so these describe the systems rather than
link to the code.

**Direct-mail platform** · NestJS · PostgreSQL · S3 · Stripe · pg-boss
API-first platform in the mould of Lob: mailing lists in, CASS-validated addresses, rendered
proofs, print production, delivery tracking out. 17 domain modules and 107 test suites, with
integration tests running against real Postgres under Testcontainers. Idempotency keys with a
24-hour replay window so a retried charge replays its outcome instead of moving money twice.
RFC 9457 problem responses from a single filter, HMAC-signed webhooks, keyset pagination over a
compound `(createdAt, id)` key, and every third-party integration bound as *real*, *fake* or
*unavailable* — so a missing production credential fails the boot rather than quietly
substituting a fake that reports success.

**Multi-jurisdiction visa platform** · Next.js · NestJS · Prisma · Stripe · AWS
One adjudication engine serving five separate visa regimes, each with its own eligibility
rules, document requirements, fee structure and government-facing format. Secure document
handling, payment capture, multi-role case management, and an internal CMS for the caseworkers
processing applications.

**EV charging infrastructure** · Python · OCPP · AWS · React · MySQL
An OCPP server speaking the open charge-point protocol to physical charging stations, with
real-time telemetry collection and a management console over the top.

**Fuel retail, four surfaces** · React Native · Node · Express · MongoDB
Customer mobile app, station management, staff operations and payments for a national fuel
retailer — one domain model behind four very different interfaces.

**Fitness app with on-device inference** · React Native · NestJS · Redis · Docker · EC2
Cross-platform app with a recommendation system over user preference and workout history, YOLO
pose inference, wearable integration, and subscription billing.

---

### Also

Taught C, C++, Python and web development to 170+ students, 2021–2024.
Explaining a thing to somebody who does not yet understand it is still the fastest way I know
to find out whether I actually understand it myself.

---

### A note on this profile

Production work lives in client and employer organisations, not here. What sits in this account
is private by obligation rather than by preference. If you want to see how I write code rather
than read about it, ask and I will walk you through a system on a call, or send a sample.

---

### Reach me

[Email](mailto:jahanzaibkhursheed2002@gmail.com) · [LinkedIn](https://www.linkedin.com/in/jahanzaibkhursheed)
