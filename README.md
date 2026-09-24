# BTC Conferences 2027

A researched list of **143 Bitcoin, mining and adjacent conferences for 2027**, as a single CSV.

Just the data. No app, no build step, no dependencies. The companion tracker app for the
2026 season lives in [BTC-Conferences-2026](https://github.com/KenobiNakamoto/BTC-Conferences-2026);
this repository is the 2027 list on its own, in the same column format, so it drops straight into
that tracker or into any spreadsheet.

*Compiled September 2026. 16 events have organiser-announced 2027 dates; the rest are
annual events projected forward from their 2026 edition.*

---

## Read the `Status` column first

2027 is far out. Most organisers have not published dates yet, so every row says how much to
trust its dates:

| Status | Rows | What it means |
|---|---|---|
| `Confirmed` | 16 | The organiser has announced 2027 dates. `Verified` names the source. |
| `Projected` | 113 | Annual event, 2027 not yet announced. **The dates are the 2026 edition's, carried forward** as a planning placeholder. Expect them to move by days or weeks. |
| `TBD` | 14 | Recurring event with no published month at all. |

**Do not book travel against a `Projected` row.** It is a diary placeholder, not an announcement.

---

## The 16 confirmed 2027 events

| Dates | Conference | Location | |
|---|---|---|---|
| January 11 – January 13 | **Max & Stacy Golf Invitational 2027** | El Salvador, El Salvador |  |
| January 16 | **Bitcoin Day Naples 2027** | Naples (FL), USA |  |
| January 29 – January 30 | **Plan B Forum El Salvador 2027** | San Salvador, El Salvador |  |
| February 4 – February 7 | **The Sovereign Summit 2027** | Miami Beach (FL), USA |  |
| February 20 | **Sound Money Soiree 2027** | Tampa (FL), USA |  |
| February 26 – February 27 | **Heatpunk Summit 2027** | Denver (CO), USA | ⛏ mining |
| March 29 | **Bitcoin For Corporations (BFC) - Strategy World 2027** | Orlando (FL), USA |  |
| March 29 – April 1 | **Strategy World 2027** | Orlando (FL), USA |  |
| April 1 – April 4 | **BitBlockBoom! 2027** | Fort Worth (TX), USA |  |
| April 22 – April 25 | **Swiss Bitcoin Conference 2027 (SBC27)** | Kreuzlingen, Switzerland |  |
| May 6 – May 8 | **BTC Prague 2027** | Prague, Czech Republic |  |
| May 11 – May 13 | **Mining Disrupt 2027** | Dallas (TX), USA |  |
| May 31 – June 2 | **Oslo Freedom Forum 2027** | Oslo, Norway |  |
| July 15 – July 17 | **Bitcoin 2027** | Nashville (TN), USA |  |
| August 26 – August 27 | **Bitcoin Asia 2027** | Hong Kong, China (HK) |  |
| TBD | **Bitcoin MENA 2027** | Abu Dhabi, UAE |  |

---

## Columns

```
Conference Name, Start Date, End Date, Month, Quarter,
City, Country, Region, Type, Bitcoin-Only, Mining Focus,
Website, Status, Notes / Key Details, Verified
```

Identical to the 2026 file, so the two are directly comparable and the tracker app imports
either one.

## Coverage

- **143 events** across **43 countries** and 9 regions
- **122** Bitcoin-only; **21** with a mining or energy focus
- By region: North America 49, Europe 43, Latin America 16, Oceania 10, TBD 7, Asia 7, Africa 6, Middle East 5, CIS/Eastern Europe 1

## Sources

Compiled from the organisers' own sites plus the public Bitcoin event directories —
[Proof of Conference](https://www.proofofconference.com/),
[bitcoinonly.events](https://bitcoinonly.events/),
[btceventsmap](https://btceventsmap.com/) and the b.tc conference family.
The `Verified` column records which source each row came from.

## Known gaps

- Mining Disrupt 2027 has a **date conflict**: its own site showed March 22–24, while Eventbrite
  and the organiser's own social profile say May 11–13, both in Dallas. The CSV carries May 11–13
  and flags it. Confirm before booking.
- Muslim Bitcoin Summit 2027 is listed as moving from London to Dallas, but the directory row
  carries an ambiguous year stamp. Treat as unconfirmed.
- Several large events (TABConf, Bitcoin Amsterdam, Baltic Honeybadger, Africa Bitcoin Conference)
  had announced nothing for 2027 at the time of compiling.

## Contributing

Corrections welcome — especially a `Projected` row you can upgrade to `Confirmed`. Open a PR
that edits `conferences-2027.csv` and cite the source in the `Verified` column.

## License

MIT.
