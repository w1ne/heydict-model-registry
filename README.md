# Heydict Model Registry

Private model registry for Heydict manifests and release-channel metadata.

## Layout

- `manifests/stt/stable.json` — stable STT model catalog consumed by desktop app.

Release assets for binaries should be uploaded to versioned tags (for example `stt-models-v1`) and referenced via `artifact_path` + app `HEYDICT_STT_MODEL_BASE_URL`.
