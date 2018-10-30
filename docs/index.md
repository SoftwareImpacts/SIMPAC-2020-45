# RefCurv

<img align="right" src="img/refcurv_logo.png" width=150px>

RefCurv is a software providing methods to create pediatric reference curves from data. The graphical user interface (GUI) is written in Python. RefCurv uses R and the [GAMLSS](https://en.wikipedia.org/wiki/Generalized_additive_model_for_location,_scale_and_shape) add-on package as the underlying statistical engine.

## Example

Following figure shows example reference curves for Body Mass Index (BMI) over age:

<p align="center">
<img src="img/bmi_example.png" class="inline" width=400px>
</p>

The curves are based on a dataset of healthy Dutch boys.
RefCurv was used to fit a model to the data points and depict it in form of percentile curves. The labels indicate the percentiles, e.g. "P3" stands for the third percentile.

## Overview

![RefCurv](/img/refcurv_0_4_0.png)