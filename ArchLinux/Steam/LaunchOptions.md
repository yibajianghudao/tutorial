## Some solution for Launch Options
### Direcx 11 error:
This error like this:  
```
Failed to initialize graphics.
Make sure you have DirectX 11 installed, have up to date
drivers for your graphics card and have not disabled
3D acceleration in display settings.
InitializeEngineGraphics failed
```
You can add this launch option to solve this error:
`PROTON_USE_WINED3D=1 %command%`
