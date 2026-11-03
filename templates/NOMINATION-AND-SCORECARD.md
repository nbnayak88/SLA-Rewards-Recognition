# Nomination, Assessment and Certificate Templates

> Mission: **Architecting Experiences for a Better World**.  
> Use in a **restricted-access** intake system; examples here contain no member data.

## Nomination dossier
```yaml
nomination_id: "DRAFT-0001"
award_code: "SB | SP | SPR | SA | SC | SV | SL"
policy_version: "draft-v1.0"
nominee_private_id: "[non-public reference]"
pathway_code: "[award-specific]"
engagement_title: "[project or achievement]"
engagement_classification: "real | simulated | mixed"
baseline_date: "YYYY-MM-DD"
baseline: "[starting position]"
objective: "[desired change]"
personal_contribution: "[actions and decisions]"
actual_result: "[verifiable achievement]"
checkpoint_evidence_ids: []
private_evidence_ids: []
independent_verifier_ids: []
ai_assistance_disclosed: false
public_recognition_opt_in: false
```

## Scorecard
```yaml
review_id: "REVIEW-0001"
nomination_id: "DRAFT-0001"
policy_version: "draft-v1.0"
conflict_of_interest: false
rubric_variant: "standard"
dimensions:
  - name: "[rubric dimension]"
    maximum: 0
    minimum: 0
    scored: 0
    evidence_ids: []
    rationale: "[why this score]"
all_mandatory_gates_passed: false
total_score: 0
overall_threshold_met: false
independent_verification_accepted: false
decision: "approve | defer | decline"
decision_date: "YYYY-MM-DD"
```

**Decision:** approve only with overall score ≥ tier threshold, every dimension minimum met, all mandatory evidence gates passed and authorized human decision.

## Certificate data
```yaml
award_id: "SLA-SA-YYYY-0001"
recipient_public_name: "[approved display name]"
award_title: "[full title]"
recognized_pathway: "[code + label]"
approved_achievement_summary: "[privacy-safe wording]"
engagement_classification: "real | simulated"
issue_date: "YYYY-MM-DD"
signatory: "[authorized name/title]"
verification_token: "[opaque non-sensitive token]"
mission: "Architecting Experiences for a Better World"
```
