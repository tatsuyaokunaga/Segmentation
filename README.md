# Nuclei Segmentation

これは、がん、心臓病、慢性閉塞性肺疾患、アルツハイマー病、糖尿病などの疾患の核の検出自動化のアルゴリズム作成タスクです。
このようなアルゴリズムが実装され、核検出の自動化が可能になれば、まれな疾患からインフルエンザまで、疾患の早期発見と早期治療実現が期待できます。
また、日本では一つの薬が世に出るまでには、優に10年を超える月日と、何百億円という莫大な費用がかかるといわれていますが、核を特定することで、より効率的な薬物検査が可能になり、各新薬が発売されるまでの期間短縮と開発費削減が期待できます。
>https://www.kaggle.com/c/data-science-bowl-2018  
>https://www.epmate.co.jp/clear/period/

## セグメンテーションとは

セグメンテーションとは、画像に対して”その画像領域の意味”を識別するという意味のことを指す。  
形状や面積といった情報が得られるため、応用先も多く、活発に研究されている。
セグメンテーションにはさらに二つの手法がある。
- Semantic Segmentation  
  - 各ピクセルにクラスのラベルを付与する問題。 
  - 応用例の一つに自動車の自動運転があり、リアルタイムでセグメンテーションが行われる。
- Instance Segmentation  
   - 個々の物体ごとにラベルを付与する問題。
   - ボトルが4本ある場合、別々のラベルを付与する
