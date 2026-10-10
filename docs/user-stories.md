# User stories

## US-01 View PO list
As a procurement manager, I want to see a list of purchase orders with status, vendor, amount and risk level, so that I can review them in one place.
- Can filter by vendor, status and risk level
- Can sort by risk score

## US-02 See overdue POs
As a procurement manager, I want overdue POs highlighted, so that I can follow up quickly.
- A PO is flagged if its promised date has passed and it is not fully received

## US-03 See POs at risk of delay
As a procurement manager, I want to see POs likely to be late before they are overdue, so that I can act early.
- Flag if due within 3 days with 0% received
- Flag if due within 5 days with under 50% received

## US-04 See repeat-delay vendors
As a procurement manager, I want to see which vendors are repeatedly late, so that I can escalate or change vendors.
- Vendor flagged at 3 or more late deliveries in 90 days

## US-05 See KPIs and charts
As a procurement manager, I want dashboard KPIs and charts, so that I can understand the overall situation.
- Shows open PO value, overdue count, risk distribution, top 5 risky vendors

## US-06 Get an AI explanation
As a procurement manager, I want a plain-language explanation of why a PO is risky, so that I understand the problem quickly.
- Explanation uses only facts from the PO data

## US-07 Get recommended actions
As a procurement manager, I want suggested next steps, so that I know what to do.
- 1 to 3 actions, each marked as a suggestion

## US-08 Keep human control
As a procurement manager, I want to stay in control of decisions, so that the AI never acts on its own.
- AI never changes or approves a PO
- Accept or dismiss is logged with user and time

## US-09 Configure thresholds
As an admin, I want to change risk thresholds without code changes, so that rules can be tuned.
- Thresholds are stored as configuration

## US-10 Work without AI
As a user, I want the app to keep working if the AI is unavailable, so that I can still see risk flags.
- Risk flags still show
- AI panel shows "explanation unavailable"
