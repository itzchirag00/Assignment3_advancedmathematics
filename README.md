Explanations

1.The NO2 feature from the dataset is visualized to understand its distribution and overall data behavior.

2.Missing values are removed to ensure clean and reliable analysis.

3.A roll-number-based non-linear transformation is applied to the NO2 values to generate a new variable 𝑧

4.The transformation introduces non-linearity and makes the problem unique for each roll number.

5.A Gaussian-like probability density function 𝑝^(𝑧)=𝑐exp(−𝜆(𝑧−𝜇)^2)is defined.

6.The parameters λ, μ, and 𝑐 are estimated from the transformed data.

7.Numerical optimization techniques are used to learn parameters that best fit the data.

8.The fitted PDF is validated using visualizations and the final parameters are submitted as required.
