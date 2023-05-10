# Gaussian_process
ガウス過程と機械学習に関するコード
## 教科書3.4と3.5のモデルをそのまま採用したコード
$$
k(x , x^{'}) = e^{\tau} \exp{\left( - \frac{(x - x^{'})}{e^{\sigma}} \right)} + e^{\eta} \delta(x , x^{'})
$$

## ランダムウォークの理論的な分散共分散行列を計算した上でのモデル化
$$
k(x , x^{\prime}) = \theta_1 \exp{\left( - \frac{(x - x^{\prime})^2}{\theta_2} \right)} + \theta_3 \delta(x , x^{\prime}) + \theta_4 \min{\{x , x^{\prime}\}}
$$