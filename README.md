# MRT Transfer Data

> 🚇 SG MRT line transfer data for the lazy or curious.

The data collated here has been converted to JSON format manually from various sources credited below.

Please reach out to me if you have any concerns or comments.

## Notes

> ⚠ This is a work-in-progress and I am tinkering around 🤪

### Separation of data files

Data is separated into 2 files per train line - `{line}_walk.json` and `{line}.json`.
The former contains the walk transfer data (tapping in and out of stations) and the latter is for normal transfer data (within a station).

### Misc.

- A door number of 0 is given for cross-platform transfers.
- Time is in seconds.
- Some data is missing e.g. door numbers for some stations

## Transfer Data Sources

Lines supported atm: EWL (green)

Data sources:

- MRT Transfer Guide -  [reddit post by u/EconomicSanction](https://www.reddit.com/r/singapore/comments/xq7srx/mrt_transfer_guide_for_the_really_kiasu/)
- MRT Transfer Timing - [reddit post by u/kiwangwa](https://www.reddit.com/r/singapore/comments/10wkygf/mrt_map_with_transfer_timing/)
- MRT Station Layout - [Land Transport Guru](https://landtransportguru.net/)

## Walk Transfer Data Sources

Lines supported atm: EWL (green)

Data sources:

- Guide and Timing - LTA Walking Train Map (WTM) viewed from [SGTrains](https://www.sgtrains.com/img/guide/travel/travel-walkmap.svg)
