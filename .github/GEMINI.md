# Gemini & Agent Guidelines for Awesome Rally

## 🚨 Critical Constraints
1. **NO Code Adjustments**: Do NOT modify, refactor, or delete any application code, scripts, or build infrastructure in this repository.
2. **Allowed Repository Edits**: The primary file that is maintained and committed is `awesome-list.yaml`. Meta-instruction files inside `.github/` (like `GEMINI.md`) are also permitted.

## 📌 Project Architecture
- **Data Source**: Driven by `awesome-list.yaml`.
- **Generator**: Powered by `derekvincent/awesome-list-generator`.
- **CI/CD Pipeline**: GitHub Actions (`.github/workflows/update-awesome-lists.yml`) automatically runs `action-awesome-list-updater` on schedule and pull requests to build updated Markdown and HTML outputs.

## 🛠️ Curation & Content Seeding Rules
- **Taxonomy Priorities**:
  1. North American Rally Events (CARS, ARA, NASA Rally Sport).
  2. Canadian Rally Resources, Clubs & Sanctioning Bodies.
  3. Dedicated Rally Training & Clinics (rally driver & co-driver specific only; exclude generic car control/autoslalom).
  4. Equipment, Safety Gear & Vehicle Prep Shops.
  5. Driver & Co-Driver Navigation/Timing Tools.
- **Workflow & Staging**:
  - Always draft proposed category and item additions in a working/staging file first before editing `awesome-list.yaml`.
  - Always audit proposed additions against existing `awesome-list.yaml` items to prevent duplicate `link_id`s or names.
  - Verify link health and structure (`link_id`, `name`, `category`, `labels`, `description`).
  - Ensure we are not duplicating entries, the same resource is ok if we are targeting different aspects, a school, and news, and a podcast. 
