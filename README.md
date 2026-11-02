# ZIP Bomb Simulator / Archive Testing Dataset

An archive-based dataset intended for educational cybersecurity research and controlled testing of archive handling and extraction behavior.

## Archive Information

| Property | Details |
|---|---|
| Archive name | GOODBYE.7z |
| Archive format | 7Z |
| Total folders | 6 |
| Total files | 526 |
| File format | `.txt` |
| Extraction password | `2026` |

## Directory Structure

The archive contains six folders:

| Folder | Number of TXT Files |
|---|---:|
| Folder 1 | 176 |
| Folder 2 | 70 |
| Folder 3 | 70 |
| Folder 4 | 70 |
| Folder 5 | 70 |
| Folder 6 | 70 |
| **Total** | **526** |

All files inside the folders are text (`.txt`) files.

## Extraction Instructions

1. Download `GOODBYE.7z` from the repository.
2. Open it using 7-Zip.
3. Enter the extraction password when prompted:

   `2026`

4. Extract the contents in an isolated test directory.

## Purpose

This archive is provided for educational exploration of:

- Compressed archive structures.
- File extraction behavior.
- Archive handling and security.
- Storage expansion analysis.
- Defensive testing of archive-processing software.

## Safety Notice

Only extract archives in a controlled environment when their contents and behavior are understood.

Do not extract potentially resource-intensive archives on production systems or devices containing important data.

## Disclaimer

This repository is intended for educational and authorized cybersecurity research. Users are responsible for ensuring that their testing activities are safe and authorized.
