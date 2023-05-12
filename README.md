# Gaussian_process
ガウス過程と機械学習に関するコードです．

ガウス過程を使いたいときは参考程度にしてみてください．

## Gaussian_Process.ipynbについて
### 教科書3.4と3.5のモデルをそのまま採用したコード
$$
k(x , x^{\prime}) = \theta_1 \exp{\left( - \frac{(x - x^{\prime})^2}{\theta_2} \right)} + \theta_3 \delta(x , x^{\prime}) 
$$

### ランダムウォークの理論的な分散共分散行列を計算した上でのモデル化
$$
k(x , x^{\prime}) = \theta_1 \exp{\left( - \frac{(x - x^{\prime})^2}{\theta_2} \right)} + \theta_3 \delta(x , x^{\prime}) + \theta_4 \min{\{x , x^{\prime}\}}
$$

## Gaussian_Process_Chapter3.ipynbについて
教科書の図を再現したコードです．教科書のイメージがつかない方は参考にしてください．
