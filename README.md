# Create the virtual env

```
python -m venv venv
```

# Activate virtual env

```
(cmd) .\venv\Scripts\activate
```

# Install Build Tools for Visual Studio

- Access this page and scroll down to Tools for Visual Studio.
https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2022

- Download Build Tools for Visual Studio and install 

# Install Visual C++ build tool

- After installing Build Tools for Visual Studio, run installer again.
- Click Modify button, select Desktop development with C++ and install more 
  + MSVC v143 - VS2022 C++ x64/x86 build tool
  + Windows (10 or 11) SDK
  + C++ CMake tools for Windows

# Install packages

```
pip install -r requirements.txt
```
