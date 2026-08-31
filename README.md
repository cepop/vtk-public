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

---

## 日本語

DIF/XML ファイルを VTK legacy 形式の `.vtk` ファイルへ変換するツールです。

この public リポジトリには、ビルド済みデスクトップアプリと README のみを
含めています。ソースコードは含まれていません。

## ダウンロード

- Windows: [`dif-vtk-converter.exe`](./dif-vtk-converter.exe)
- macOS: [`DIF-VTK-Converter-macOS.zip`](./DIF-VTK-Converter-macOS.zip)

## 使い方

### Windows

`.xml` または `.dif` ファイルを `dif-vtk-converter.exe` へドラッグ&ドロップ
してください。

### macOS

`DIF-VTK-Converter-macOS.zip` を展開し、`.xml` または `.dif` ファイルを
`DIF VTK Converter.app` へドラッグ&ドロップしてください。

アプリを直接開いた場合は、ファイル選択ダイアログが表示されます。

## 出力

変換後のファイルは、入力ファイルと同じ場所に作成される `vtk_output`
フォルダへ保存されます。

既存の `.vtk` ファイルは上書きせず、連番つきのファイル名で保存します。

詳細ログは `vtk_output/convert_log.txt` に出力されます。

## チェックサム

SHA-256:

```text
63cffd60bb69f73fc5f3bd59c4c84657e916dad604deab34dfa40d867780360d  dif-vtk-converter.exe
412821ce168e05f63dee50481ad8c12fe0768ee1178af41d052c53d426d2b9ed  DIF-VTK-Converter-macOS.zip
```

## 注意事項

- 変換ツールは VTK legacy ASCII `POLYDATA` ファイルを書き出します。
- このアプリはローカルファイル変換用途を想定しています。
- 患者データや機微情報を含む生成ファイルは公開しないでください。

## ライセンス

非商用目的でのみ利用できます。商用利用には事前の書面による許可が必要です。
