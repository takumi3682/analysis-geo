# Project

## Structure (recommended)
- `data/raw` : **増設SSD** に実体（プロジェクト内はシンボリックリンク）
- `data/processed` : **内蔵SSD** に実体（レンダリング安定のため）
- `outputs` : **増設SSD** に実体（プロジェクト内はシンボリックリンク）
- `reports` : Quarto (`.qmd`)
- `docs` : 公開HTML（GitHub Pages 用、`_quarto.yml` の `output-dir`）

## Notes
- 公開されるのは `docs/` の中身だけです（GitHub Pages 設定）。
