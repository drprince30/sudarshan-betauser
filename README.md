# Sudarshan Beta User Download

This public repository is for beta downloads only.

The private Sudarshan source repository is not published here. This repo intentionally contains only packaged download artifacts, manifest, and checksum metadata.

## Download

- SUDARSHAN_BETAUSER_WINDOWS_EXE.zip - Windows packaged beta build
- SUDARSHAN_BETAUSER_MANIFEST.json - build manifest for the ZIP

## Verify

Use PowerShell:

``powershell
Get-FileHash -Algorithm SHA256 .\SUDARSHAN_BETAUSER_WINDOWS_EXE.zip
``

Expected SHA256:

``text
9E80F1ED6CA3AFEA180923166F93298C0B0E42076EE5AAD8100741C4F239FADF
``

## Notes

- Build version: 0.1.0
- Source commit used by private build pipeline: 18c4ee6
- Windows may show a security warning for unsigned beta builds.
- Use only on repositories you own or are authorized to test.
- This beta is local-first and defensive-use only.
- Qwen model weights are not bundled. Beta users can install Ollama separately and run ollama pull qwen2.5-coder:7b.
- No GitHub token or private source repository access is required for beta users.
