logging.basicConfig 常用的參數與說明:
- `level：顯示日誌的等級`
- `filename：log 的檔名`
- `format：log 的輸出格式`
- `datefmt：輸出時間的格式`
- `filemode：日誌開啟模式`
- `handlers：與filename與stream不相容，無法同時使用`
- `stream：與handlers不相容，無法同時使用`
- `style：formatter 使用 ％ 還是 {} 還是 $`

logging format 常用輸出格式:
- `%(asctime)s：日期時間`
- `%(filename)s：模組檔名`
- `%(funcName)s：函式名稱`
- `%(levelno)s：行數`
- `%(levelname)s：logging level`
- `%(levelno)s：logging level 的數值`
- `%(message)s：訊息`
- `%(module)s：模組名稱`
