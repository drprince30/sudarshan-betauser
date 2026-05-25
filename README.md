# Sudarshan Beta User Download

This public repository is for beta downloads only. It does not contain Sudarshan private source code, tests, datasets, training files, secrets, tokens, or model weights.

## Download And Run

1. Download `SUDARSHAN_BETAUSER_WINDOWS_EXE.zip`.
2. Extract the ZIP.
3. Open the extracted folder.
4. Run `Sudarshan.exe`.
5. Sudarshan opens on localhost, usually `http://127.0.0.1:8767`.

## First Run Local Model Setup

Sudarshan is local-first. Your code stays on your machine. The selected local AI model runs through Ollama on localhost. Sudarshan does not upload your repository to our server.

If Ollama is not installed, install it from https://ollama.com/download, then restart Sudarshan or click Recheck on the setup page.

Choose the model that fits your hardware:

- `qwen2.5-coder:0.5b`: fastest, lowest quality
- `qwen2.5-coder:1.5b`: light
- `qwen2.5-coder:3b`: recommended for 16GB RAM
- `qwen2.5-coder:7b`: better quality, slower/heavier
- `qwen2.5-coder:14b`: advanced/heavy
- `qwen2.5-coder:32b`: advanced/heavy

First run can pull the selected model using Ollama, test it locally, and save the choice. Qwen model weights are not bundled in this ZIP.

## Verify

Use PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 .\SUDARSHAN_BETAUSER_WINDOWS_EXE.zip
```

Expected SHA256:

```text
3B587DD7F54A7AA838E9C54990E3B5660D03740E720B9B06397F6E92A9F4D8C2
```

## Build Notes

- Build version: `0.1.1`
- Source commit used by private build pipeline: `b470728`
- Windows may show a security warning for unsigned beta builds.
- Use only on repositories you own or are authorized to test.
