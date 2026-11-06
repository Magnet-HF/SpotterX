# Setup and compatibility

## Download

Download the package from [SpotterX Releases](https://github.com/Magnet-HF/SpotterX/releases). The [original Mag-Windows release](https://github.com/Magnet-HF/Mag-Windows/releases/tag/SpotterX-v4.0) remains available.

## Compatibility status

The available original package is tagged `SpotterX-v4.0`. Its preserved [installation instructions](package/JS8SuperSpotter_Install_Instructions.txt) describe a Python launch workflow and required packages; [Linux](package/README.linux) and [macOS](package/README.macos) notes are also included. These are publisher-supplied instructions, not independently verified platform certifications.

The bundled README records testing against older JS8Call versions. Compatibility with the current MagNet Subspace build requires developer confirmation.

## First-run outline from the supplied package

1. Read the [package installation guide](package/JS8SuperSpotter_Install_Instructions.txt) and its dependency notes before launch.
2. Extract the package to its own writable folder. Preserve the blank database template; back up an existing database before upgrading.
3. In JS8Call's Reporting settings, enable the TCP Server API, acceptance of TCP requests, and station-information setting as described in the [bundled README](package/README.txt).
4. Start JS8Call, then launch `js8spotter.py` using the package's Python instructions. Set your callsign and grid and match the connection address and port.
5. Confirm received activity appears before relying on the station workflow.

The package contains overlapping historical instructions. The MagNet installation guide is retained in full so the developer can reconcile those instructions against the current build.

## Developer handoff

Please complete this page with:

1. Supported operating systems and architectures.
2. Compatible JS8Call edition and versions.
3. Package contents and exact launch instructions.
4. Required runtime and dependency versions.
5. JS8Call API and connection settings.
6. Which forms and map resources are included; whether a separate forms download is required.
7. Upgrade, backup, and rollback instructions.
8. A short first-run check and known issues.

General station-integration documents belong in the MagNet hub and should be linked from here rather than copied.
