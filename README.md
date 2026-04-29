# Organic Reaction Outcome Predictor

## Overview
This project builds a dataset to predict organic reaction outcomes (SN1, SN2, E1, E2) using substrate, reagent, solvent, and temperature.

## What I Did
- Built ~30 reaction examples
- Identified the correct mechanism for each
- Wrote explanations based on organic chemistry rules

## How It Works
Each reaction is analyzed using:
- Substrate type (methyl, primary, secondary, tertiary)
- Reagent (nucleophile/base strength)
- Solvent (polar protic or aprotic)
- Temperature (room temp or heat)

## Example
2-bromobutane + NaOCH3 in methanol  
→ SN2/E2 competition

Reason:
Secondary substrate allows both substitution and elimination. Methoxide is a strong nucleophile and base, so both pathways are possible.

## Project Goal
To organize chemistry knowledge in a structured way that can be used to test and improve AI predictions.

## Next Steps
- Test AI predictions (ChatGPT, Claude)
- Score accuracy
- Identify common mistakes

## Files
- data/ → dataset (CSV file)
- analysis/ → AI evaluation notes
