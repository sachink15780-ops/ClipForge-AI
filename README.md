# ClipForge AI — Creator Clipping Studio ✂️

Premium responsive frontend prototype for a video clipping workflow.

## Frontend
- Video/stream URL form
- Clip count and length controls
- 9:16 vertical and 16:9 landscape toggles
- Subtitle language/style controls
- Auto zoom, burn subtitles and face tracking toggles
- Creator channel watchlist saved in browser localStorage
- Project library with save, copy details and delete
- Mobile-responsive dashboard

## Current limitations — honest status
This is a **frontend prototype**. It does not yet download/process YouTube media, generate MP4 clips, run AI highlight detection, monitor creators in the background, or export subtitle files. Saving a project currently saves settings/metadata, not actual video clips.

## Next backend work
- Authenticated backend API and job queue
- FFmpeg processing worker for real crop/export in 9:16 and 16:9
- Speech-to-text and moment scoring to choose highlights
- Subtitle rendering/style templates
- Safe source ingest for media that users own or are authorized to process
- Background creator live-status monitoring and notification workflow using compliant source access
- Storage for generated files and secure download links
- Per-user data isolation, access controls, rate limiting, retention, and deletion

## GitHub Pages
Workflow: `.github/workflows/pages.yml`. Enable Pages in Settings → Pages and choose GitHub Actions if it is not already enabled.
