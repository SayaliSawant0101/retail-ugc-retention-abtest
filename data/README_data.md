# Data

This project uses a **synthetic dataset** generated for an A/B testing case study.

## File
- `retail_paid_vs_organic_ugc_experiment.csv`

## Grain
- 1 row = 1 user (first-time purchaser)

## Key fields
- `acquisition_channel`: paid vs organic  
- `variant`: control vs treatment (paid users only), benchmark (organic users)
- `ugc_email_sent_date`, `ugc_email_opened`, `ugc_email_clicked`: treatment exposure + engagement
- `repeat_purchase_within_30d`: primary outcome
- `returned_within_14d`: guardrail
- `repeat_order_value`, `discount_used_on_repeat`: repeat behavior quality proxies

## Notes
Organic users are included as a benchmark cohort and are **not randomized**.
