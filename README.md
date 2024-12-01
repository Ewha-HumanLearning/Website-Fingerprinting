# 👾 Website-Fingerprinting
2024-02 Machine Learning

## 📝 Problem Definition
Website fingerprinting is a powerful technique used to identify and categorize specific websites by analyzing distinctive patterns in network traffic. This method allows attackers to recognize particular websites a user visits based on traffic characteristics, even without direct access to the user's device or browser. Such fingerprinting poses a significant privacy threat, especially in anonymizing networks like Tor, which are designed to mask users' identities and protect against surveillance. However, fingerprinting techniques can undermine the anonymity provided by networks like Tor, enabling malicious actors to infer users' browsing activities, thereby compromising their privacy and anonymity.


## 🌲 Structure

```sql
.
├── README.md
├── data
│   └── data_preprocessing.ipynb
└── model
    └── model_implementation.ipynb
```

## ✨ How To Run

1. Download the files `data_preprocessing.ipynb` and `model_implementation.ipynb`.
2. Upload the files `mon_standard.pkl` and `unmon_standard10_3000.pkl` to Colab and set their paths in `data_preprocessing.ipynb`
    
    ```sql
    mon_path = "./mon_standard.pkl"
    unmon_path = "./unmon_standard10_3000.pkl"
    ```
    
3. Run the preprocessing code and download the preprocessed data.
4. Upload the preprocessed data to Colab. Set the file path in `model_implementation.ipynb`:
    
    ```sql
    with open("./processed_mon_data_closed_world.pkl", "rb")
    ```
    ```sql
    with open("./processed_binary_data_open_world.pkl", "rb")
    ```
    ```sql
    with open("./processed_multiclass_data_open_world.pkl", "rb")
    ```
    
5. Run the model. Note that due to RAM error, each scenario must be executed separately.

    Note: If you mount Google Drive to Colab, use the following code:
     ```sql
     from google.colab import drive
     drive.mount('/content/drive')
     ```
     Modify the file path appropriately.
    ```sql
    with open("./drive/MyDrive/processed_binary_data_open_world.pkl", "rb")
    ```
   


## 🫧 Contributors
| <img width=150px src="https://github.com/sujinRo.png"/> | <img width=150px src="https://github.com/zziyuni.png"/> | <img width=150px src="https://github.com/hyunihs.png"/> | <img width=150px src="https://github.com/suhhyun524.png"/> | <img width=150px src="https://github.com/yunji118.png"/> |
| --- | --- | --- | --- | --- |
| 노수진 | 윤지윤 | 이정현 | 최수현 | 하윤지 |
| [sujinRo](https://github.com/sujinRo) | [zziyuni](https://github.com/zziyuni) | [hyunihs](https://github.com/hyunihs) | [suhhyun524](https://github.com/suhhyun524) | [yunji118](https://github.com/yunji118) |
