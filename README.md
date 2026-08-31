# DIF VTK Converter

DIF/XML files to legacy VTK `.vtk` files converter.

This public repository contains only the prebuilt desktop apps and this README.
Source code is not included.

## Downloads

- Windows: [`dif-vtk-converter.exe`](./dif-vtk-converter.exe)
- macOS: [`DIF-VTK-Converter-macOS.zip`](./DIF-VTK-Converter-macOS.zip)

## Usage

### Windows

Drag and drop `.xml` or `.dif` files onto `dif-vtk-converter.exe`.

### macOS

Unzip `DIF-VTK-Converter-macOS.zip`, then drag and drop `.xml` or `.dif`
files onto `DIF VTK Converter.app`.

If you open the app directly, it shows a file selection dialog.

## Output

Converted files are written to a `vtk_output` folder next to the input file.
Existing `.vtk` files are not overwritten; numbered filenames are used instead.

Detailed logs are written to `vtk_output/convert_log.txt`.

## Checksums

SHA-256:

```text
63cffd60bb69f73fc5f3bd59c4c84657e916dad604deab34dfa40d867780360d  dif-vtk-converter.exe
412821ce168e05f63dee50481ad8c12fe0768ee1178af41d052c53d426d2b9ed  DIF-VTK-Converter-macOS.zip
```

## Notes

- The converter writes VTK legacy ASCII `POLYDATA` files.
- The app is intended for local file conversion.
- Do not publish patient data or generated files that contain sensitive data.

## License

Use is permitted for non-commercial purposes only. Commercial use requires prior
written permission.
