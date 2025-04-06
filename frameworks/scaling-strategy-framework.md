# Scaling Strategy Framework

## 1. Vertical Scaling Approach

**Campaign Name:** `SIRFRANCIS_VSCALE_[SOURCE]_[DATE]`

### Budget Increment Strategy
| Performance Metric | Action | Increment |
|-------------------|--------|-----------|
| CAC ≤ 25 SAR | Aggressive Scaling | +30% every 3 days |
| CAC 26-35 SAR | Moderate Scaling | +20% every 5 days |
| CAC 36-40 SAR | Conservative Scaling | +10% every 7 days |
| CAC > 40 SAR | Maintain/Optimize | No increase |

### Implementation Method
```
Step 1: Identify campaign meeting scaling criteria for 3+ consecutive days
Step 2: Duplicate winning campaign (preserve original as control)
Step 3: Increase budget according to performance bracket
Step 4: Monitor daily for 3 days without optimization
Step 5: If performance maintained, continue scaling; if degraded, revert to previous budget
```

### Risk Management
- Set performance alerts for CAC increases >15%
- Implement automatic rules to decrease budget if CAC exceeds 45 SAR
- Never increase budget by more than 50% in a single week
- Create "safe mode" duplicate campaigns at original budget levels

## 2. Horizontal Scaling Approach

**Campaign Name:** `SIRFRANCIS_HSCALE_[EXPANSION]_[DATE]`

### Audience Expansion
| Expansion Type | Implementation | Risk Level |
|----------------|----------------|------------|
| Lookalike Extension | Increase LAL from 1% to 2%, then 3% | Medium |
| Interest Expansion | Add related interests to existing sets | Medium |
| Geographic Expansion | Add tier 2 cities after success in tier 1 | Low |
| Age Expansion | Extend to adjacent age brackets | Low |
| Placement Expansion | Add new placements to successful campaigns | Medium |

### Creative Expansion
| Approach | Implementation | Testing Period |
|----------|----------------|---------------|
| Winning Element Isolation | Identify successful elements, create variations | 7 days |
| Format Extension | Adapt winning creatives to new formats | 7 days |
| Seasonal Adaptation | Modify winning creatives for seasonal relevance | Event-based |
| Product Extension | Apply winning frameworks to other products | 7 days |

## 3. New Product Launch Scaling

**Campaign Name:** `SIRFRANCIS_LAUNCH_[PRODUCT]_[DATE]`

### Phase 1: Testing (Days 1-7)
- Budget: 200-300 SAR/day per platform
- Multiple audience variations
- Multiple creative variations
- Objective: Identify winners, CAC < 40 SAR

### Phase 2: Early Scaling (Days 8-14)
- Budget: 500-700 SAR/day per platform
- Focus on top 2-3 audiences
- Focus on top 2-3 creatives
- Objective: Stabilize CAC < 35 SAR

### Phase 3: Full Scaling (Days 15+)
- Budget: 1,000+ SAR/day per platform
- Expand winning audiences
- Refresh winning creatives
- Objective: Maintain CAC < 35 SAR at volume

## 4. Platform-Specific Scaling Considerations

### TikTok
- Learning phase: Minimum 50 conversions per week
- Budget increases: Preferably before 2pm Saudi time
- Ideal scaling: 15-20% increases with 3-day intervals
- Creative refresh: Every 7-10 days to prevent fatigue

### Snapchat
- Learning phase: Minimum 40 conversions per week
- Budget increases: Recommended at 20% increments
- Creative refresh: Every 10-14 days
- Leverage Collection Ads for cross-product promotion

### Instagram
- Learning phase: Longer than TikTok/Snapchat (≈7 days)
- Budget increases: More conservative (10-15%)
- Focus on quality signals (engagement rate, saved posts)
- Leverage high-end lifestyle content for prestige positioning

## 5. Monitoring Framework for Scaled Campaigns

| Metric | Healthy Range | Warning Threshold | Action Threshold |
|--------|---------------|-------------------|------------------|
| CAC | ≤35 SAR | 36-40 SAR | >40 SAR |
| ROAS | ≥5x | 4-4.9x | <4x |
| CTR | ≥1.2% | 0.8-1.1% | <0.8% |
| CPC | ≤2 SAR | 2.1-2.5 SAR | >2.5 SAR |
| Frequency | ≤3 | 3.1-4 | >4 |

### Daily Monitoring Tasks
- Check CAC/ROAS by campaign, ad set, and ad
- Monitor frequency scores for audience fatigue
- Check for creative fatigue (declining CTR)
- Review audience saturation (rising costs)

### Weekly Analysis
- Compare performance to previous periods
- Evaluate budget utilization efficiency
- Review new audience/creative tests
- Plan next scaling actions

## 6. Emergency Response Plan

| Scenario | Action Plan |
|----------|------------|
| Sudden CAC Increase (>30%) | 1. Pause worst-performing ads<br>2. Reduce budget by 30%<br>3. Check for platform issues<br>4. Review audience overlap |
| Conversion Tracking Issues | 1. Validate pixel/SDK implementation<br>2. Switch to intermediate goals temporarily<br>3. Contact platform support |
| Creative Fatigue | 1. Inject fresh creatives<br>2. Rotate existing creatives<br>3. Reduce frequency caps |
| Seasonal Performance Drops | 1. Adjust offers/messaging<br>2. Temporarily reduce CAC targets<br>3. Shift budget to better-performing platforms |