# Fountain

API Evangelist profile of **Fountain** — an AI-powered frontline workforce platform that helps high-volume employers source, screen, hire, onboard, schedule, and retain hourly workers across QSR, retail, logistics, hospitality, healthcare, manufacturing, grocery, and franchise operations.

Fountain's integrated suite spans an ATS, candidate CRM, agentic sourcing (**Source**), digital onboarding with background-check and document workflows, shift and scheduling for active workers, and an orchestration layer (**Cue**) that automates workflows across products. Three AI agents — **Anna** (recruiter screening), **Emma** (24/7 candidate support), and **Sam** (employee engagement) — sit across the funnel and the post-hire workforce.

## APIs

Fountain exposes a versioned REST API at [developer.fountain.com](https://developer.fountain.com/), with a machine-readable index at [developer.fountain.com/llms.txt](https://developer.fountain.com/llms.txt).

- **Hire API v2** — applicants, funnels/openings, stages, calendar slots, labels, locations, hiring goals, custom exports, webhooks, custom integrations.
- **Worker API** — post-hire worker profiles, employment records, document submissions, I-9 verification, attendance, shifts, demands, allowances, breaks, holidays, audience and workforce management, brand management.

### Authentication

API requests authenticate via the `X-ACCESS-TOKEN` header using tenant API keys created under Developer Settings, or via OAuth 2.0 against the shared service hire base URL (`https://services.fountain.com/api/servicehire/v2`) for partner integrations.

## Resources

- Website: <https://www.fountain.com>
- Developer portal: <https://developer.fountain.com/>
- API reference: <https://developer.fountain.com/reference/overview>
- Partner portal: <https://partners.fountain.com>
- Status page: <https://status.fountain.com/>
- Trust center: <https://trust.fountain.com/>
- Support: <https://support.fountain.com/en/>

Profiled by [Kin Lane](https://apievangelist.com), API Evangelist.
