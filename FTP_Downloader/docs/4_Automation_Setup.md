# ⏰ 4. Automation Setup

When automation is enabled:
- The software will automatically connect to the configured FTP servers every night at **00:10**.
- It will fetch all new daily files and store them locally.

### How It Works
- Settings are saved persistently in `settings.json`.
- The scheduler runs a background job using the `schedule` Python module.
- The job checks for new files daily and downloads only missing data.



