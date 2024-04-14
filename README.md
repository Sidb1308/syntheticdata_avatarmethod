# syntheticdata_avatarmethod
Synthetic data generation using the "Avatar" method introduced by Guillaudeux &amp; al.
Today, it is widely acknowledged that the risk of re-identification using data pseudonymization methods is significant, presenting a considerable challenge,
particularly in the context of personal health data. The high risk of re-identification poses a serious threat to individuals' privacy and can lead to severe consequences. 
Patients entrust their personal health information to healthcare institutions with the expectation that it will be safeguarded and used responsibly.
However, if these data can be re-identified, it represents a breach of that trust. 
Nonetheless, value is also created by re-analyzing, sharing, and eventually licensing out data. 
The challenge here is to generate synthetic data that preserves the patient's privacy and retains the statistical value of the dataset.
We are going to generate synthetic data using the “Avatar” method, introduced by Guillaudeux et al. in the publication that you can find here: https://www.nature.com/articles/s41746-023-00771-5. 
The Avatar method is patient-centric (i.e., it uses the characteristics of a single patient as the starting point of its statistical modeling). 
Even though each individual is at the origin of the creation of their avatar simulation, they do not directly contribute to the local modeling of their Avatar generation,
which I believe is a very clever way to generate synthetic data that will meet the conditions mentioned above.

The dataset comes from the Global Open Source Severity of Illness Score (GOSSIS) initiative by MIT and were collected in the United States in 2021."
A variable notebook briefly describing the variables is also available (file: cahierVariables.csv)

