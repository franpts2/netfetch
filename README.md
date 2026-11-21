# netfetch

A small file-download client in C, built for a computer networks lab.

<p align="left">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
</p>

## About

netfetch is a short lab project implementing a file-download client in C. It is meant to be run in the course's network lab, with the setup notes in `manualconfig-guide.md`.

## Project Structure

- `download.c`: Main C source implementing the download client.
- `manualconfig-guide.md`: Manual configuration and setup notes used during the lab.
- `script.md`: Automation / run script notes or examples used to exercise the client.

## Requirements

- A POSIX-compatible system (Linux tested).
- `gcc` (or compatible C compiler).

## Quick Start

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

## Team & Course

**Team**

This project was developed by:

- [Francisca Portugal](https://github.com/franpts2)
- [Maria Luiza Vieira](https://github.com/maluviieira)

**Course**

Developed for the **RCOM (Computer Networks)** course in 2025/26 at FEUP (Faculty of Engineering, University of Porto).

## License

Coursework submitted at FEUP. Shared for reference; all rights reserved unless stated otherwise.

---

_netfetch — fetch the file, understand the wire._
