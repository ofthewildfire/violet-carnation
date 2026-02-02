# Notes

To run you need to activate virtual environment:

- `.venv\Scripts\Activate.ps1` on Windows for Powershell
- `source .venv/Scripts/activate` Windows Bash
- `source .venv/bin/activate` Linux, MacOS

Run: 

```bash
fastapi dev main.py
```
which will start the dev server. 

If the command does not exist install FastAPI - but only <b>after</b> you have set up the virtual environment: 

```bash
pip install "fastapi[standard]"
```
---

## Resources 

https://fastapi.tiangolo.com/tutorial/#install-fastapi

https://www.devsheets.io/sheets/fastapi

https://youtu.be/8TMQcRcBnW8