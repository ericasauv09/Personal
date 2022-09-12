\[**Product Managers**: Open this ticket **at least 2 Sprints (4 weeks)** before you expect a Platform Staging Review of this Product/Feature.  Then:
- Replace title's **[Product/Feature]** with your actual product/feature name.
- Add yourself to Assignees
- Fill-out sections below.]

**See also**: Relevant [PTEMS-QA Manual-UI Testing process doc](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/teams/vsa/engineering/qa/manual-ui-testing-process.md) for details.

## Product/Feature summary

\[Provide brief summary of product/feature to be tested on Staging by PTEMS-QA. Also, be sure to include links to the Product/Feature Outline, Epic, Pre-Launch Checklist, and Design tickets/artifacts.]

- [Product Outline](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/products/identity-personalization/my-va)
- [Feature Epic](https://github.com/department-of-veterans-affairs/va.gov-team/issues/43332)
- Product/Feature Copy deck(s): \[provide link, or type "In Design prototypes"]
- Product/Feature Design prototypes: \[provide link(s)]

## Product-team SMEs

\[For any Practice-areas worked by 2+ team-member, clarify who specifically is assigned to this initiative/project. Leave blank for other areas.\]

Design/Research: Angela Agosto
Content/IA: 
Front-end: Taylor Mitchell
Back-end: 
QA: Tze-chiu Lei

## Proposed use-cases and Staging test-accounts

\[Provide specific Use Cases (all the different interactive user-flows and data-specific states) to be tested.  Use **[this Product Use Cases template](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/teams/vsa/design/product-use-cases-template.md)** -- copy the template's markdown into a new .md file inside your Product folder [next to Product Outline file], then start updating.

IMPORTANT for authenticated products (requiring sign-in): Staging test-users must be provided for all authenticated scenarios, and Staging-API test-data created to match the account-specific scenarios.]

[Link to **Use Cases doc**](https://github.com/department-of-veterans-affairs/va.gov-team-sensitive/blob/master/Administrative/vagov-users/staging-test-accounts-myva-payment-info-v2.md)

## How to configure this issue

- [X] **Product Manager** added to Assignees
- [ ] Attached to a **Milestone** (when will this be completed?)
- [X] Attached to **Epic** (what body of work is this a part of? possibly `Ongoing Maintenance`)
- [X] Added product-specific label (if any)

## Definition of Done

- [ ] Product references provided by Product Team.
- [ ] Use Cases provided.
- [ ] For authenticated products, Staging test-accounts and mock-data set up for Use Cases above.
- [ ] Test Cases [in TestRail] finalized based on Use Cases above.
- [ ] Test Runs completed on Staging [or Drupal pre-prod environment].
- [ ] Test Reports generated.  These should be provided to Platform at least 4 workdays before [Staging Review](https://depo-platform-documentation.scrollhelp.site/collaboration-cycle/Staging-review.1810137181.html).
