# FreeCORE release delta — samba

[FreeCORE](https://freecore.org) carries the TrueNAS CORE 13.3 system
forward as an independently maintained operating system on FreeBSD.
TrueNAS CORE 13.3 systems upgrade straight to FreeCORE 15.0 in place,
then continue on the project’s update train.

Not affiliated with or endorsed by iXsystems, Inc.

## What this repository is

`0001-freecore-samba-release-delta.patch` is the reviewed FreeCORE release delta against
[`truenas/samba`](https://github.com/truenas/samba). The
multi-gigabyte upstream repository is not duplicated here.

| | |
|---|---|
| **Base** | truenas/samba truenas/v4-24-stable @ 2026-08-10 |
| **Base commit** | `e7df0a31a95db824642546bb32ad73b25fcc660a` |
| **Base resolves publicly** | yes |
| **Licence** | GPL-3.0 |

## Applying

```sh
git clone https://github.com/truenas/samba.git
cd samba
git checkout e7df0a31a95db824642546bb32ad73b25fcc660a
git apply --index /path/to/0001-freecore-samba-release-delta.patch
```

## Public history

This is one source-state delta, not an export of the development history.
Private commit subjects, bodies, issue references, dates, ordering, and
intermediate churn are not present. Release tags identify states that were
actually built and validated.

## Contributors represented in this delta

- FreeCORE
- Andreas Schneider
- Andrew Bartlett
- Andrew Walker
- Arvid Requate
- Bjoern Jacke
- Björn Jacke
- Brian Meagher
- Christof Schmitt
- David Mulder
- Douglas Bagnall
- Gabriel Nagy
- Jeremy Allison
- Jones Syue
- Joseph Sutton
- Jule Anger
- Martin Schwenke
- MikeLiu
- Noel Power
- Pavel Filipenský
- Ralph Boehme
- Samuel Cabrero
- Shachar Sharon
- Stefan Metzmacher
- Volker Lendecke

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Security reports go to
security@freecore.org, not to the issue tracker — see
[SECURITY.md](SECURITY.md).

## Licence and attribution

See [NOTICE](NOTICE) and [TRADEMARKS.md](TRADEMARKS.md). Nothing here is
relicensed; upstream copyright notices and licence texts are preserved.
