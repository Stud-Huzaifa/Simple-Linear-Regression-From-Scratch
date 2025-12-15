# Simple-Linear-Regression-From-Scratch
This project implements Linear Regression from scratch in Python, without using machine learning libraries.

Linear Regression from Scratch

This project implements Linear Regression from scratch in Python, without using machine learning libraries.

The goal is to understand how linear regression works internally instead of treating it as a black box.

What this covers

Mean-centered data

Covariance and variance

Slope and intercept calculation

Basic prediction logic

Importance of data shape

Formula used

Slope

𝑚
=
∑
(
𝑥
−
𝑥
ˉ
)
(
𝑦
−
𝑦
ˉ
)
∑
(
𝑥
−
𝑥
ˉ
)
2
m=
∑(x−
x
ˉ
)
2
∑(x−
x
ˉ
)(y−
y
ˉ
	​

)
	​


Intercept

𝑏
=
𝑦
ˉ
−
𝑚
𝑥
ˉ
b=
y
ˉ
	​

−m
x
ˉ
Usage
lr = MineLR()
lr.fit(X_train, y_train)
predictions = lr.predict(X_test)

Key takeaway

Linear Regression is not magic — it’s understanding relationships in data.

Requirements

Python 3

NumPy
