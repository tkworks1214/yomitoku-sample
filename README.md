# yomitoku-sample

## Set up

1. `yomitoku` をインストール
    ```
    python -m pip install --no-cache-dir --retries 30 --timeout 180 yomitoku
    ```

## Usage

```
yomitoku ./images/image1.pdf  --lite -d cpu -o results/image1 -f md
```

- `--lite`: 軽量モードで実行
- `-d`: `cpu` or `cuda`
- `-f`: `md`, `json`, `csv` などの出力フォーマット
