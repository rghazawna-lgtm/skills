# strategy-mapper

Show a strategy mapping for the given company profile.

## Examples

- "What is the best entry model for Blackview?"
- "Map a strategy for a PCBA manufacturer"

## Instructions

Call the `run_js` tool with the following exact parameters:

- data: A JSON string with the following fields
  - model_selection: Based on the profile, select from (Space Model, Setup Support, Operational Model, Service Center).
  - reasoning: One sentence explaining why this model fits the lead.
