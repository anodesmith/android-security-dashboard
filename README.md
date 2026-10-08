# Day 13 - Android Security Dashboard UI

> Day 13 of 14 in the **Zero to Production Infrastructure & Security** series.

Extends the Day 12 app to visualise SIEM alerts and live security metrics.

| | |
|---|---|
| **Day** | 13 of 14 |
| **Status** | Under construction |
| **Verification** | `./gradlew --offline ktlintCheck` |
| **Tags** | `kotlin`  `android`  `jetpack-compose`  `dataviz`  `siem` |

## Focus

- JSON alert model parsing
- Real-time UI state management
- Custom Compose chart rendering
- Alert severity presentation

## Status

Implementation lands during the Day 13 build session. Until then this
repository holds the agreed structure only - there is no placeholder code here
pretending to work.

The nightly pipeline appends the real verification result to [STATUS.md](STATUS.md).

## Layout

```
13-android-security-dashboard/
  README.md        this file
  LICENSE          MIT
  STATUS.md        machine-written verification record
  .gitignore       shared from the series root
  .gitattributes   forces LF endings so bash scripts run on Windows
```

## Verify

```bash
./gradlew --offline ktlintCheck
```

The nightly job at 22:00 runs this command, records the result and
exit code in STATUS.md, then tags and pushes the repository.

## Licence

MIT. See [LICENSE](LICENSE).