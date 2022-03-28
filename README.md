# Music-Genre-Classification
Machine Learning and Deep learning techniques to Classify Music Genre

## Techniques Used
- KNN
- Logistic Regression
- Nalive Bayes
- Decision Tree
- Random Forest
- SVM
- Artificial Neural Networks
- CNN

Classifiers         | Accuracy | F-Score
KNN                 | 0.68     | 0.7
SVM                 | 0.66     | 0.67
Logistic Regression **| 0.72     | 0.73**
Naive Bayes         | 0.5     | @.51
Decision Tree       | 0.45     | 0.45
Random forest       | 0.63     | 0.64
ANN                 **| 0.68     | 0.72**
CNN                 | 0.33     | 0.35

## Confusion Matrix for Top performing Model
! [image] (data:image/png;base64,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wPcz5tsG+CS6f1aeM27hsuvG8cbceXyxejV9h4zgonNHMXLo4KRjVatZs2Zcf9VYzhlzIamKFCcMH0b3brslHatGobUxhJc5tLwQxrbc79ET2bHfLrRs34qTP76cuTe8xI59d6Fd7x3Bna+XrGbWeX9MOma1QmjjykLblkNs48bIqhqLzMmCzboCT0e9NpjZlOjx1E3PAQcAdwKHkK77lrj7YDNrR7o4ag78P+Bj4GFgJfAScIa7dzWzfsDl7l7jlh7aEJgVFSUdISteHu4RL1J/QtuOASa3ujnpCFkbtfaKpCNkJcTvixC3ZVq2yeug1Manns/Z39lmw4/OS/Z66wFy9yXAXhmPz6rmuZ9W8dpVpIujTLtn3L8umm8GMCN+WhEREdlq2gdIREREpOFLeh8gERERCV2A3SkqgERERCSeAM9jFGDNJiIiIhKPeoBEREQknvA6gFQAiYiISEwBFkAaAhMREZGCox4gERERiSfAnaBVAImIiEg8AY4nBRhZREREJB71AImIiEg84Y2AqQASERGRmALcB0hDYCIiIlJw1AMkIiIi8YTXAaQCSEREROIJcASsMAogKypKOkKj5mvLk46QNWsV3jah7bj+jVp7RdIRsjawKKzM01fdkHSErHl5gN9xLdskHaHBK4gCSEREROpRk/C6gFQAiYiISDzh1T86CkxEREQKj3qAREREJJ4A94JWASQiIiLxhFf/aAhMRERECo96gERERCSeAHuAVACJiIhIPAEeBq8hMBERESk46gESERGReMLrAFIBJCIiIjEFeBi8hsBERESk4KgHSERERGIKrwdIBZCIiIjEoyEwERERkYZPPUAiIiIST3gdQOoB2hozZ83m2KHHc/TgYUya/FDSceoktMyfrljBmZddzqCzzmbwT87hkSeeTDpSra6+aQKHHDeYIaeekXSUOgttu4DwMoeQ99LJp/NY2UTuW3DN5mm77L0Tt8/+GffNv5pxfzqPou+3TDBhzUL87IWYuUZmubvliQqgLKVSKcZPmMgD993N9GlTefqZZ1n8rw+SjlWjEDM3bdqUsef9lOlTHuR3997NY3/8E4uXfJR0rBqNGDSQ+++4PekYdRbidhFa5lDyvjDl71w34N7vTLvkgdN46Mo/cv7eE5g97S1G/vyohNLVLrTPHoSZubFRAZSl+QsXsXPnznTu1IkWzZsz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)

## Top 20 Features
![image](https://user-images.githubusercontent.com/5665@508/160325648-2b745d30-78db-4bb0-9645-f0alefcle947.png)
