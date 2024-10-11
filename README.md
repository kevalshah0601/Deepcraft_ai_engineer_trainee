# Stock Price Prediction Model
# 株価予測モデル

## English

### Description
This project implements a stock price prediction model using LSTM neural networks. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and backtesting. The model is designed to predict the closing price of NTT stock based on historical data.

### Features
- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA) with visualizations
- LSTM model implementation using PyTorch
- Hyperparameter tuning
- Ensemble modeling
- Backtesting
- Cross-validation

### Requirements
- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- torch
- japanize-matplotlib

### How to Run
1. Ensure you have all the required libraries installed. You can install them using pip:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn torch japanize-matplotlib
   ```

2. Place your `stock_price.csv` file in the same directory as the script.

3. Run the script using Python:
   ```
   python stock_price_prediction_model.py
   ```

4. The script will automatically load the data, perform EDA, train the models, and display the results.

### Output
The script will generate various plots and metrics, including:
- Stock price trends
- Feature importance analysis
- Model performance evaluation (MSE, MAE, R^2)
- Backtesting results

## 日本語

### 説明
このプロジェクトは、LSTMニューラルネットワークを使用した株価予測モデルを実装しています。データの前処理、探索的データ分析（EDA）、特徴量エンジニアリング、モデルのトレーニング、評価、バックテストが含まれています。このモデルは、過去のデータに基づいてNTT株の終値を予測するように設計されています。

### 機能
- データの前処理と特徴量エンジニアリング
- 可視化を含む探索的データ分析（EDA）
- PyTorchを使用したLSTMモデルの実装
- ハイパーパラメータチューニング
- アンサンブルモデリング
- バックテスト
- クロスバリデーション

### 要件
- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- torch
- japanize-matplotlib

### 実行方法
1. 必要なライブラリがすべてインストールされていることを確認してください。pipを使用してインストールできます：
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn torch japanize-matplotlib
   ```

2. `stock_price.csv`ファイルをスクリプトと同じディレクトリに配置します。

3. Pythonを使用してスクリプトを実行します：
   ```
   python stock_price_prediction_model.py
   ```

4. スクリプトは自動的にデータを読み込み、EDAを実行し、モデルをトレーニングして結果を表示します。

### 出力
スクリプトは以下のようなさまざまなプロットと指標を生成します：
- 株価トレンド
- 特徴量重要度分析
- モデルのパフォーマンス評価（MSE、MAE、R^2）
- バックテスト結果
