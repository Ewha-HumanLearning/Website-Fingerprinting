# 👾 Website-Fingerprinting
2024-02 Machine Learning

## 🌲 Structure

```sql
.
├── README.md
├── data
│   └── data_preprocessing.ipynb
└── model
    └── model_implementation.ipynb
```

## ✨ How To Use

1. Download the files `data_preprocessing.ipynb` and `model_implementation.ipynb`.
2. Upload the files `mon_standard.pkl` and `unmon_standard10_3000.pkl` to Colab and set their paths in `data_preprocessing.ipynb`
    
    ```sql
    mon_path = "./mon_standard.pkl"
    unmon_path = "./unmon_standard10_3000.pkl"
    ```
    
3. Run the preprocessing code.
4. Upload the preprocessed data to Colab. Set the file path in `model_implementation.ipynb`:
    
    ```sql
    	with open("./processed_mon_data_closed_world.pkl", "rb")
    ```
    
5. Run the model. Note that due to RAM error, each scenario must be executed separately.

## 🫧 Contributors
| <img width=150px src="https://github.com/sujinRo.png"/> | <img width=150px src="https://github.com/zziyuni.png"/> | <img width=150px src="https://github.com/hyunihs.png"/> | <img width=150px src="https://github.com/suhhyun524.png"/> | <img width=150px src="https://github.com/yunji118.png"/> |
| --- | --- | --- | --- | --- |
| 노수진 | 윤지윤 | 이정현 | 최수현 | 하윤지 |
| [sujinRo](https://github.com/sujinRo) | [zziyuni](https://github.com/zziyuni) | [hyunihs](https://github.com/hyunihs) | [suhhyun524](https://github.com/suhhyun524) | [yunji118](https://github.com/yunji118) |
