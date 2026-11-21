# ToolRadar Downloads

Companion files for ToolRadar YouTube videos. Free to use with the tutorials on the channel.

## Files

- **n8n-workflow.json** — The n8n workflow from the ElevenLabs AI receptionist video ("Build an AI Receptionist That Books Appointments by Itself"). Import it into n8n via *Workflows → Import from File*. It receives a booking from the ElevenLabs voice agent and appends it to a Google Sheet through an Apps Script relay.
- **sheet-template.csv** — Header row for the "ElevenLabs Bookings" Google Sheet used in the same video (`timestamp, name, service, date, time, phone`). Create a sheet with this header, then point the workflow's relay at it.
