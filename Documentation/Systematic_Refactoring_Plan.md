# BizBox Systematic Refactoring Plan

## Current Data Inventory
- **Tree Structure Records**: 27 files
- **L1 Foundations Split**: 6 files  
- **L2 Records Split**: 21 files
- **L3 Records Split**: Available
- **L4 Records Split**: Available

## Refactoring Strategy

### Phase 1: Fix Granularity Issues in Current Tree
1. **L1 Audio Equipment** - Remove product specifics, broaden to foundation level
2. **L2 True Wireless Earbuds** - Remove AirPods analysis, keep market overview
3. **L2 Content Creation** - Verify appropriate granularity
4. **L2 Design Software** - Verify appropriate granularity

### Phase 2: Integrate Existing L1/L2 Data
1. **L1_003_DESIGN_SOFTWARE** → Integrate into Digital Commerce Tree
2. **L2_001_AI_DESIGN_TOOLS** → Place under appropriate L1 parent
3. **L2_002_MARKETPLACE_PLATFORMS** → Integrate into E-Commerce branch
4. **L2_003_CREATIVE_SOFTWARE** → Integrate into Creator Tools branch

### Phase 3: Create Missing L3/L4 Records
1. **L3 Audio Processing Implementation** (from L2 TWS)
2. **L4 AirPods Patent Landscape** (moved from L2)
3. **L3 AI Design Implementation** (from L2 AI Design Tools)
4. **L4 Creator Payment Patents** (existing, verify placement)

### Phase 4: Ensure Classification Precision
- **L0**: 2-3 digit NAICS, 2-4 digit UNSPSC, 1-3 char CPC
- **L1**: 3-4 digit NAICS, 4-6 digit UNSPSC, 3-4 char CPC  
- **L2**: 4-5 digit NAICS, 6-8 digit UNSPSC, 4-5 char CPC
- **L3**: 5-6 digit NAICS, 8-10 digit UNSPSC, 5-6 char CPC
- **L4**: Full classification + specific context

## Implementation Priority
1. Fix current granularity mismatches
2. Integrate valuable existing data
3. Create proper hierarchical progression
4. Ensure consistent classification precision

