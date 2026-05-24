# Sudarshan Beta User Download

This public repository is for beta downloads only.

The private Sudarshan source repository is not published here. This repo intentionally contains only packaged download artifacts and checksum metadata.

## Download

- `SUDARSHAN_BETAUSER_WINDOWS_EXE.zip` - Windows packaged beta build

## Verify

Use PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 .\SUDARSHAN_BETAUSER_WINDOWS_EXE.zip
```

Expected SHA256:

```text
72AAA4BBC19791890CE328BCF3C87207BE9DB04539DEF9FD89375DCBBFFBB900
```

## Notes

- Windows may show a security warning for unsigned beta builds.
- Use only on repositories you own or are authorized to test.
- This beta is local-first and defensive-use only.
