# QSAR-models
QSAR (Quantitative Structure Activity relationship) is a computational method based on mathematic models also mechchine learning combination. To stduy correlation between a chemical compound's structure and its biological activity (e.g., IC₅₀, EC₅₀, etc.). QSAR model is built from training data and is validated by test data. To split these data was used Kannard stone algorithm which is a data selection based on a distance metric between data points. 

This implementation was adapted from the scikit-learn library and further developed by our CU-SHU team.

Sinsulpsiri S, Nishii Y, Xu-Xu QF, Miura M, Wilasluck P, Salamteh K, Deetanya P, Wangkanont K, Suroengrit A, Boonyasuppayakorn S, Duan L. Unveiling the antiviral inhibitory activity of ebselen and ebsulfur derivatives on SARS-CoV-2 using machine learning-based QSAR, LB-PaCS-MD, and experimental assay. Scientific Reports. 2025 Feb 26;15(1):6956.

# Data preparation
1. The dataset was organized in a table containing X and Y variables, where X represents the biological activity (pIC₅₀) and Y represents the molecular descriptors, as shown in the 27-inhibitors.csv file.
2. Save them as csv.

# Using model
You may customize this code to fit your specific conditions, such as adjusting the proportion of data splitting, modifying model parameters, or altering training configurations. Additionally, ensure that the data file path is correctly specified for your local environment.
