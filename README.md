# netfetch — Download Client

Short lab project implementing a file-download client in C.

## Repository contents

- `download.c`: Main C source implementing the download client.
- `manualconfig-guide.md`: Manual configuration and setup notes used during the lab.
- `script.md`: Automation / run script notes or examples used to exercise the client.

## Requirements

- A POSIX-compatible system (Linux tested).
- `gcc` (or compatible C compiler).

## Build

Compile the program with:

```sh
gcc download.c -o download
```

If additional flags are needed for your environment (e.g., `-pthread`), add them accordingly.

## Usage

This program is meant to be used in an appropriate lab.

See `script.md` and `manualconfig-guide.md` for example runs and configuration steps used in the lab.

## Notes

- This README is intentionally minimal; refer to `manualconfig-guide.md` for network setup, test cases, and manual verification steps.
- If you want, I can extend this README with a full example run, expected output, or a small test harness.

## Development Team

This project was developed by:

- [Francisca Portugal](https://github.com/franpts2)
- [Maria Luiza Vieira](https://github.com/maluviieira)

## Course Information

Developed for the RCOM (Computer Networks) course at FEUP (Faculty of Engineering, University of Porto).
