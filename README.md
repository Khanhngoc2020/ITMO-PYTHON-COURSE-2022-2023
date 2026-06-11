# ITMO Python Course 2022-2023

Consolidated laboratory work from the ITMO Python programming course,
completed during the 2022-2023 academic year.

## Contents

| Lab | Period | Main topics |
| --- | --- | --- |
| [Lab 01](Lab01/) | 2022 | CSV processing, filtering, and file output |
| [Lab 02](Lab02/) | 2022 | Console graphics, functions, and CSV statistics |
| [Lab 03](Lab03/) | 2022 | Collections and an inventory optimization problem |
| [Lab 04](Lab04/) | 2022 | Tkinter GUI, images, audio, and key generation |
| Lab 05-06 | - | Not present in the original repositories |
| [Lab 07](Lab07/) | 2023 | NumPy/Pandas data processing and visualization |
| [Lab 08](Lab08/) | 2023 | OpenCV image and video processing |
| [Lab 09](Lab09/) | 2023 | Notebook exercise and Flask/PostgreSQL web app |
| [Lab 10](Lab10/) | 2023 | Speech recognition and dictionary API integration |

## Repository history

This repository combines the following original repositories:

- `Lab1.PyITMO`, `Lab2.PyITMO`, `Lab3ITMO`, and `Lab4ITMO`
- `ITMO-PYTHON-2023`
- `ITMO_PYTLAB`

The separate `Python-2023` repository duplicated the Lab 08 assignment and is
therefore represented by the more complete Lab 08 copy above.

Large committed virtual environments from the original repositories were not
included. Create a fresh environment and install only the packages needed for
the lab you want to run.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Some labs require additional system services or hardware:

- Lab 04 uses a desktop GUI and audio output.
- Lab 09 web app requires PostgreSQL and environment variables described in
  [`Lab09/web-app/README.md`](Lab09/web-app/README.md).
- Lab 10 requires a microphone and may require a system PortAudio package.

