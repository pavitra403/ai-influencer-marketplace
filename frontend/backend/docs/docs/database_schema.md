# Database Schema (Basic)

## Users
- id
- name
- email
- role (brand/influencer)
- niche
- engagement_rate
- followers

## Campaigns
- id
- brand_id
- title
- description
- budget
- niche_required
- created_at

## Applications
- id
- campaign_id
- influencer_id
- status (pending/approved/rejected)
- applied_at
