# Ontology for Dairy Production

## Description
This ontology represents the structure of a dairy production system. It includes dairy farms, cattle, milk production, feed, processing, supply chain, and quality control.

## Classes (TBox)
- **DairyFarm**: Represents a dairy farm.
- **Cattle**: Represents cows and livestock.
- **Milk**: Represents produced milk.
- **Feed**: Represents different types of cattle feed.
- **Processing**: Represents milk processing stages.
- **SupplyChain**: Represents the distribution system.
- **QualityControl**: Represents regulatory standards.

## Properties
- **hasCattle**: Dairy farm has cattle.
- **producesMilk**: Cattle produce milk.
- **consumesFeed**: Cattle consume feed.
- **isProcessedInto**: Milk is processed.
- **isDistributedBy**: Processed milk is distributed.
- **isRegulatedBy**: Milk quality is controlled.

## Instances (ABox)
- `Farm1` (DairyFarm) has `Cow1` (Cattle).
- `Cow1` produces `MilkBatch1` (Milk).
- `Cow1` consumes `GrassFeed` (Feed).
- `MilkBatch1` is processed into `Pasteurization` (Processing).
- `Pasteurization` is distributed by `SupplyChain1` (SupplyChain).
- `MilkBatch1` is regulated by `QualityStandard1` (QualityControl).

## Usage
This ontology can be used for AI-driven dairy farm management, milk quality tracking, and supply chain optimization.

