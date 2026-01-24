# Shopify DAP Log

Daily, append-only log of my Design Apprentice Program experience at Shopify.

## Format
- One JSON object per line (`log.jsonl`)
- One entry per day
- Append only

## Schema

### Mandatory
- `date` (string, YYYY-MM-DD)
- `activity` (string)
- `people` (string[])
- `in-office` (boolean)

## Rules
- Log every day
- All schema fields are required
- Keep entries short and factual
- Append only (no edits)

## Purpose
- Capture compounding learnings over time
- Track who influences growth
- Create a durable record of the DAP year