# Verify the DAMS Community Edition Download

Official v1.0.0 installer:

DAMS_Community_Edition_1.0.0_Setup.exe

Expected SHA-256:

9BA56AB5529BAD52F5720189955F9990C7B8EE7A1A4848E53402393C2C51ECE6

## Windows PowerShell

Run:

    Get-FileHash ".\DAMS_Community_Edition_1.0.0_Setup.exe" -Algorithm SHA256

If the returned SHA-256 differs from the expected value above, do not treat that file as the certified v1.0.0 release.
