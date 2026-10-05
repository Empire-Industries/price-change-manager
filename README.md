# Empire Price Change Manager

A desktop tool Empire Industries staff use to check and load price changes
into Microsoft Dynamics GP. This repository holds release downloads only.
There is no source code here.

## Download

Open **Releases** on the right and take the newest one.

| File | For |
|---|---|
| `empire-price-change-manager-windows-x64.exe` | Windows. Double-click it. |
| `empire-price-change-manager-linux-x64` | Linux. `chmod +x` it, then run it. |
| `SHA256SUMS.txt` | Checking the download arrived intact. |

## Check the download

On Windows, in PowerShell:

    Get-FileHash .\empire-price-change-manager-windows-x64.exe -Algorithm SHA256

The hash must match the line for that file in `SHA256SUMS.txt`.

## First run on Windows

The executable is not code-signed, so Windows shows "Windows protected your
PC" the first time. Choose **More info**, then **Run anyway**.

## Updates

The tool checks this repository once when it starts. When a newer version is
out, it opens a window saying what is new, with a link here (1.19.0 shows a
link in its header instead). It never downloads anything by itself.

## Support

Issues are turned off here. Ask your Empire IT contact.
