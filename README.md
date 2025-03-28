# Footprint  
**AIを活用した犬の行動分析とソリューション提供Webサービス**
![image](https://github.com/user-attachments/assets/1b8c6bf1-822e-4e42-aa6f-e86446541c3c)

---

## 概要

Footprintは、飼い主が愛犬の動画をアップロードすることで、AIが行動や感情を分析し、  
状況に応じた解決策（ソリューション）を提案するサービスです。  
初めて犬を飼う方でも、行動の意味を理解し、適切に対応できるようサポートします。

---

## 主な機能

- **行動分析**：10〜30秒の動画をAIが解析し、行動を可視化
- **感情分析**：行動と状況を入力として、DNNで感情（安心、不安など）を分類
- **ソリューション提供**：Gemini APIと専門書籍に基づく適切な対応策を提示
- **犬種分類**：写真から犬種を推定し、上位3種と確率を表示
- **日記機能**：犬の成長過程を記録・保存可能

![image](https://github.com/user-attachments/assets/a0e5a377-cb9b-469a-b0d4-513dc6ef2f8a)
行動分析UI

![image](https://github.com/user-attachments/assets/905f7992-daca-4e11-bf7e-47c8f5400845)
犬種分類UI

![image](https://github.com/user-attachments/assets/254caa01-4aa9-458e-b43a-a01d0771e62f)
ダイアリーUI

---

## 担当業務（個人）

- **バックエンドと行動分析AIの開発**
  - Flaskを用いたWeb APIサーバーの構築
  - MoviNet A2モデルを活用した行動分類AIの構築と最適化
  - レイヤー凍結後に全体ファインチューニングを行う2段階学習で精度を向上
  - GCP上のVM環境でAIモデルのデプロイとWebサーバーを構築

---

## 使用技術

- Python, Flask, TensorFlow  
- MoviNet A2
- Google Cloud Platform（VM, Cloud SQL, Storage）

![image](https://github.com/user-attachments/assets/9a79d0ff-adc2-4888-bca6-f807c4423925)
クラウド設計

---

## 目的

- 犬の行動理解不足による飼育放棄の防止
- AIによる個別対応型の行動ケア提供
- ペット産業におけるデータ活用型サービスの新提案


