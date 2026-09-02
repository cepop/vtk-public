# DIF VTK Converter

DIF/XML files to legacy VTK `.vtk` files converter.

This public repository contains only the prebuilt desktop apps and this README.
Source code is not included.

This application was developed by the author as a convenience tool. The
converted VTK file format is described in this README.

## Downloads

- Windows: [`dif-vtk-converter.exe`](https://raw.githubusercontent.com/cepop/vtk-public/main/dif-vtk-converter.exe)
- macOS: [`DIF-VTK-Converter-macOS.zip`](https://raw.githubusercontent.com/cepop/vtk-public/main/DIF-VTK-Converter-macOS.zip)

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
- If you encounter a problem, please open an Issue with your operating system,
  app version, input file type, error message, and clear reproduction steps.
- Do not publish patient data or generated files that contain sensitive data.

## License

Use is permitted for non-commercial purposes only. Commercial use requires prior
written permission.

## Disclaimer

The binaries are provided as-is. To the maximum extent permitted by applicable
law, the author provides no warranty of any kind and assumes no liability for
any damage, loss, malfunction, data issue, or other problem arising from use of
the software. Users are responsible for determining whether the software is
appropriate for their own environment and purpose, and for all results of using
it.

This wording follows the general approach used by common open source licenses
such as the [MIT License](https://opensource.org/license/mit/) and
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), which provide
software as-is and limit warranty and liability.

---

## 日本語

DIF/XML ファイルを VTK legacy 形式の `.vtk` ファイルへ変換するツールです。

この public リポジトリには、ビルド済みデスクトップアプリと README のみを
含めています。ソースコードは含まれていません。

本アプリケーションは、作成者が利便性のために開発したものです。変換された
VTK ファイルの仕様は、この README に記載の通りです。

## ダウンロード

- Windows: [`dif-vtk-converter.exe`](https://raw.githubusercontent.com/cepop/vtk-public/main/dif-vtk-converter.exe)
- macOS: [`DIF-VTK-Converter-macOS.zip`](https://raw.githubusercontent.com/cepop/vtk-public/main/DIF-VTK-Converter-macOS.zip)

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
- 使用上の問題などがありましたら、使用環境、アプリのバージョン、入力ファイル
  の種類、エラーメッセージ、再現手順などを明記の上、Issue に記載してください。
- 患者データや機微情報を含む生成ファイルは公開しないでください。

## ライセンス

非商用目的でのみ利用できます。商用利用には事前の書面による許可が必要です。

## 免責事項

このバイナリファイルは現状有姿で提供されます。適用法令により認められる
最大限の範囲で、作成者はいかなる種類の保証も行わず、本ソフトウェアの使用
に起因または関連して生じた損害、損失、不具合、データ上の問題、その他一切
の問題について責任を負いません。

本ソフトウェアが利用者の環境や目的に適しているかの判断、および使用に伴う
結果については、すべて利用者自身の責任に属します。

この記載は、[MIT License](https://opensource.org/license/mit/) や
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) など、
広く使われているオープンソースライセンスに見られる「現状有姿での提供」、
「保証の否認」、「責任制限」の考え方を参考にしています。
