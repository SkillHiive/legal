# SkillHive Privacy Policy

**Last updated:** July 17, 2026

SkillHive ("we," "us," "the platform") is a community-run, open-source project — not currently a registered company. It is operated by contributors who have come together to build and maintain it. This policy explains what we collect, why, and what we do (and deliberately do not) do with it.

If you have questions about this policy, contact us at **privacy@skillhiive.com**.

---

## 1. Who we are

SkillHive is an open-source, ambient co-presence platform for developers. It is currently maintained as a community initiative, based in India, with the intention of eventually registering as a formal open-source organization. Until that registration happens, SkillHive is run by its contributors as a volunteer effort.

Our source code — frontend, backend, and the exact configuration running our LiveKit servers — is public on GitHub. The code you can inspect there is the same code deployed to production through our CI/CD pipeline.

## 2. Minimum age

You must be at least **13 years old** to use SkillHive.

## 3. What we collect

At signup, we collect:
- Email address
- Password (see Section 5 on how this is stored)
- Username
- Display name

After onboarding, you may optionally upload an **avatar** through your profile settings. This is entirely your choice and is not required.

**Posts** (projects, media, or offer letters/showcases) that you choose to submit are stored as user-generated content tied to your account.

We do **not** currently track online/presence status (e.g. whether you're active in a room at a given moment).

## 4. What we don't collect

We do not run any analytics engines or tracking scripts on SkillHive. There is no behavioral tracking, no engagement analytics, and no third-party trackers anywhere in our stack. This is a deliberate choice, in line with our philosophy of building an ambient environment rather than an engagement-optimized product.

The only thing stored on your device related to your session is a **session token**, used to keep you signed in. We do not use marketing, advertising, or analytics cookies of any kind.

## 5. Video and audio (LiveKit)

Rooms and calls on SkillHive are powered by a **self-hosted LiveKit** deployment that we run ourselves — not a third-party managed service.

- We do **not record** audio or video from any session.
- Logging on our LiveKit servers is turned off.
- Because our backend, frontend, and infrastructure configuration are all public on GitHub, you (or anyone) can verify these claims against the exact code and configuration running in production.

## 6. Where your data lives

Our backend runs on **self-hosted Supabase** (PostgreSQL), installed via Supabase's official Docker setup, on infrastructure we control ourselves — not Supabase's managed cloud offering. Our frontend is hosted on **Vercel**.

## 7. Content verification

Because offer letters and project showcases are a core part of SkillHive, we make an effort to verify their authenticity before or after posting, to keep the platform genuine and prevent fake accounts or fabricated content from flooding the community.

## 8. Content ownership

You retain full ownership of anything you post on SkillHive. By posting, you grant SkillHive a license to display that content on the platform. We do not claim ownership of your work.

## 9. Account deletion

You can request deletion of your account and all associated data at any time.

- **Currently:** email **support@skillhiive.com** to request deletion. (An in-app self-service deletion option is in active development.)
- When an account is deleted, all data tied to that account — posts, comments, and anything else linked to your user ID — is removed via our database's relational integrity. Nothing is retained after deletion.

## 10. Moderation and your data

Posts that are off-topic or without discussion value may be removed, with a warning sent to the poster. After two such warnings, an account may be banned. Moderation decisions are currently made directly by the project's maintainer; a dedicated moderation team is planned for the future as the platform grows.

Maintainers who work on SkillHive's code do not have standing access to delete or alter user data or content as part of their development role — that access is separate from day-to-day feature and bug-fix work.

## 11. Governing law

This policy is governed by the laws of India, and any disputes relating to it are subject to Indian jurisdiction.

## 12. Changes to this policy

As SkillHive is an actively developing community project, this policy may be updated as the platform evolves (for example, once account deletion is fully self-service, or once a dedicated moderation team is in place). We will update the "Last updated" date above when changes are made.

## 13. Contact

Questions about this policy or your data: **privacy@skillhiive.com**
General support, including account deletion requests: **support@skillhiive.com**
