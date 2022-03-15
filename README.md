# GXPlain: Gaussian mixture based EXplanations

## Abstract
The popular GXPlain(Gaussian mixture based local interpretable model agnostic EXplanations) framework suffers from the
confounding issue of inconsistent explanations which renders it completely useless for safety-critical
domains like healthcare and robotics, where the notion of trustworthiness and consistency are of
the utmost importance. In this work, a novel modification of LIME based on Gaussian Mixture
Models based clustering called GXPlain(Gaussian Mixture based Local Interpretable
Model Agnostic Explanations) is proposed. A thorough analysis showcasing the performance of the
proposed technique on five real-world datasets is done, and the superior stability and fidelity of the
algorithm using metrics like Kendall’s W and R2
score is demonstrated.

## Evaluation

The evaluation was done for the dollowing datasets and models over metrics like Kendall's W(for stability) and R2 score(for fidelity). The notebooks for all the datasets can be found in the root folder.
![image](https://user-images.githubusercontent.com/49980787/158472372-26549d4f-c576-4d41-85ae-72bc8adbc817.png)

## Results

Our approach got better fidelity and stability than LIME for all the 5 datasets

* Stability
![image](https://user-images.githubusercontent.com/49980787/158472633-a51c8782-9faa-4f58-a1e2-a7d8e5b85c11.png)

* Fidelity
![image](https://user-images.githubusercontent.com/49980787/158472686-04c3c9c0-abbd-44b2-90c8-d120813a4fec.png)

Preprint coming out soon!

## License

[MIT License](https://github.com/adityasaini70/Applications-of-GMM-in-XAI/blob/main/LICENSE)
