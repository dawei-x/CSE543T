# CSE543T

### Overview

Algorithmic recourse refers to 
> [^ar]providing explanations and recommendations to individuals who are unfavorably treated by automated decision-making systems.

[^ar]: Amir-Hossein Karimi, Gilles Barthe, Bernhard Scholkopf, and Isabel Valera. [A survey of algorithmic recourse: contrastive explanations and consequential recommendations.](https://dl.acm.org/doi/full/10.1145/3527848) ACM Computing Surveys, 55(5):1–29, 2022.

This repository contains report and code for my comparative project **A Study of Algorithmic Recourse** as part of `CSE 543T: Algorithms for Nonlinear Optimization` taught by [Dr. Yixin Chen](https://engineering.wustl.edu/faculty/Yixin-Chen.html). 

We appreciate that the python libriry [ReLax](https://github.com/BirkhoffG/jax-relax) supports fast, light-weight evaluation. 

This report involves the evaluation of three algorithmic recourse methods: `Wachter et al.`[^w] `DiCE`[^d] and `ProtoCF`[^p] on three datasets: `Adult`[^ad] `Oulab`[^ou] and `Heloc`[^he]

[^w]: Sandra Wachter, Brent Mittelstadt, and Chris Russell. Counterfactual explanations without opening the black box: Automated decisions and the gdpr. *Harvard Journal of Law & Technology*, 31:841, 2017-2018.
[^d]: Ramaravind K Mothilal, Amit Sharma, and Chenhao Tan. Explaining machine learning classifiers through diverse counterfactual explanations. In *Proceedings of the 2020 conference on fairness, accountability, and transparency*, pages 607–617, 2020.
[^p]: Arnaud Van Looveren and Janis Klaise. Interpretable counterfactual explanations guided by prototypes. In *Machine Learning and Knowledge Discovery in Databases. Research Track: European Conference, ECML PKDD 2021, Bilbao, Spain, September 13–17, 2021, Proceedings, Part II 21*, pages 650–665. Springer, 2021.
[^ad]: Ronny Kohavi and Barry Becker. UCI machine learning repository. [https://archive.ics.uci.edu/ml/datasets/adult](https://archive.ics.uci.edu/ml/datasets/adult), 2017.
[^ou]: Jakub Kuzilek, Martin Hlosta, and Zdenek Zdrahal. Open university learning analytics dataset. *Scientific data*, 4(1):1–8, 2017
[^he]: [Home Equity Line of Credit(HELOC)](https://www.kaggle.com/datasets/averkiyoliabev/home-equity-line-of-creditheloc)

### Readme for CSE 543T Grader:
To run the notebook [Exps.ipynb](./Exps.ipynb), it is highly recommended to open it with Google Colab. 

If you are a Colab new user &rarr; On Colab, please head to `Runtime` &rarr; `Change runtime type` &rarr; `Hardware accelerator` &rarr; `GPU`. Then `Runtime` &rarr; `Run all`.

