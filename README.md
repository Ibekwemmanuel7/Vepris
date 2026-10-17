# Vepris

Forestry intelligence component of [Lillie US](https://github.com/Ibekwemmanuel7/Lillie_US), intended for the Southern United States.

**Status: design stage.** This repository contains a scope brief, not an implemented or validated monitoring service. No customer, pilot partner, performance target or commercial outcome has been established.

## Intended customer and first workflow

The proposed first user is a forestry consultant or timberland manager responsible for several private forest properties. The proposed first workflow is prioritising stands for field inspection after an observed canopy change, storm or other disturbance.

A future output would combine dated observations, stand boundaries, change maps, observation quality and a field-review record. Its usefulness, timeliness and cost must be established against the manager's existing workflow before it becomes a product commitment.

## Forestry scope to design

- Forest condition and canopy-change screening.
- Drought and other stress investigation support.
- Harvest and land-clearing histories, using management records for context.
- Replanting and vegetation-recovery tracking.
- Storm-disturbance documentation and inspection priorities.
- Portfolio reporting for landowners, forestry advisers and timberland managers.

These are candidate capabilities, not implemented features. Initial geography, forest type, observation cadence and acceptance criteria still require a dedicated pilot design.

## Component boundaries

| Component | Responsibility |
|---|---|
| Vepris | Forest condition, management changes, recovery and forestry inspection workflows |
| [Vantage](https://github.com/Ibekwemmanuel7/Vantage) | Agriculture and farmer/adviser workflows; separately designed |
| [VHAGAR](https://github.com/Ibekwemmanuel7/VHAGAR) | Wildfire detection, prescribed-burn context and burned-area processing |
| [Vaughan](https://github.com/Ibekwemmanuel7/vaughan) | Hurricane research methods; not a general forest-damage service |
| [Vulcan](https://github.com/Ibekwemmanuel7/Vulcan) | Mineral-prospectivity research |

Vepris may eventually consume reviewed VHAGAR fire-event products and use them in forestry recovery reports. That interface is proposed, not implemented. Do not duplicate the fire engine or imply that linking repositories creates an operational integration.

## Evidence and limits

Any future pilot must retain source dates, uncertain or missing observations, independent field references and management context. A change flag is a reason to investigate; it does not by itself diagnose pests, disease, illegal harvesting or a specific cause. Timber volume, financial valuation, forest-carbon credits and engineering or insurance conclusions require their own methods and validation.

## Next design decisions

1. Confirm the paying customer and existing inspection workflow.
2. Select a bounded Southern geography and forest-management type.
3. Select one inspection decision and the last useful delivery time.
4. Obtain consented stand boundaries, management records and field observations.
5. Define baselines, acceptance criteria, observation-gap handling and delivery cost before implementation.

Lillie US records this repository as a planned component. Its documentation commit is traceable, but it is not an installable Python dependency or a deployed service.
