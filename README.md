# Migration-Example
- This repository contains an example of migration of a Gemini API example from Python To Javascript using Deno and Jupyter notebook.
---

## Prerequisites
- **Operating System**: Windows, macOS, or Linux.
- **Jupyter**: Jupyter Notebook or JupyterLab must be installed.

## for macOS and Linux:
```
curl -fsSL https://deno.land/install.sh | sh
```
## for windows Powershell
``` bash
iwr https://deno.land/install.ps1 -useb | iex
```
## Run Jupyter command
``` cmd
deno jupyter --unstable
```
## Verify kernel installation
```cmd
jupyter kernelspec list
```
**Add dependencies using the deno.json file**

## Install requirments using deno.json 
**For example**
```
{
    "imports": {
      "@google/genai": "npm:@google/genai"
    }
  }
```

