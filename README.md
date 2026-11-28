## My contributions (Mahyar)

Team project, forked from reham0138/store-app- to showcase my part of the work. I worked mainly on the frontend, UI design, and testing.

**Authentication UI**

- Built the login and register pages with client-side validation, an `AuthProvider`/`useAuth` context, and `ProtectedRoute` role guards (PR #5).

**Design**

- Contributed to the visual design: color palette, logo, and UI styling (see `crown_anchor_design_reference`).

**Testing / QA**

- Tested the app manually across the three roles (customer, branch manager, admin) and across branches: login and role redirects, catalog search/filter/pagination, cart and checkout, order status flow, reviews, and dashboards.
- Checked edge cases such as invalid form input, insufficient stock at checkout, and access to pages with the wrong role.
- Reported issues to the team; test cases and results are documented in `docs/TEST_PLAN.md`.

**Frontend and API contract alignment (AI-assisted)**

- Directed and reviewed a migration of the frontend to a versioned API contract (PR #24): service layer with an Axios client and JWT handling, normalized API errors, string IDs, paginated lists, review upsert, and order status flow.
- Added mock-mode seed data (admin plus one manager per branch) so every dashboard could be demoed without a backend.

**AI-assisted work:** most of PR #24 was implemented with an AI coding agent (Devin) under my direction. I reviewed, tested, and merged it.

**Tech stack:** React, TypeScript, Vite, Tailwind CSS, React Router, Axios. The backend (NestJS + MongoDB) was built by teammates.

**Live demo:** TODO
**Screenshots:** TODO
