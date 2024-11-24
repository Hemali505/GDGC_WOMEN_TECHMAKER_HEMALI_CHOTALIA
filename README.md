Hemali Chotalia
23BHI10073
GDG
WTM
TASK1
_
_
Blockchain-Based Scholarship Fund: Bridging the Gender
Gap in STEM
It leverages blockchain technology to create a decentralised, transparent
scholarship fund for women in STEM.
Gender Inequality in STEM:
1.Women represent only 28% of the global STEM workforce.
2.They deal with educational biases and discriminatory hiring practices.
3.Financial constraints prohibit many women from pursuing advanced
degrees in STEM professions.
Fig 1:Women in T ech Statistics
Current Scholarship Challenges:
● Lack of Transparency: Traditional scholarship programs can
suffer from corruption or misallocation of funds.
● Bias and Inequality: Women in STEM face systemic barriers in
accessing funding and educational resources.
● Trust Issues: Donors are often unsure whether their contributions
are reaching deserving candidates.
Key features:
● Transparency: All transactions are permanent and visible to all
participants.Increases confidence between funders, recipients, and
stakeholders.
● Decentralisation: No central authority; reduces corruption and
bias.Democratic access to funds and verification processes.
● Global Access: Blockchain transcends borders, allowing women
from any region to apply.Reduces administrative costs and
bureaucracy.
● Financial efficiency: Reduces brokers and operational costs,
allowing more resources to reach recipients.
Technical Steps:
1. Blockchain Platform:
○ Ethereum: For its smart contract capabilities and wide
adoption.
○ Hyperledger: For enterprise-grade solutions and scalability.
2. Smart Contracts:
○ Defining criteria: Academic performance, financial need,
personal statement.
○ Automate fund release upon verification.
3. User Interfaces:
○ Donor Portal: T o view impact metrics and donation history.
○ Applicant Portal: Secure submission of personal details and
verification documents.
4. Partner with Educational Institutions:
○ Integrate university databases for real-time academic
verification.
Smart Contract Workflow (Detailed Example)
Technology Stack
Blockchain:
● Ethereum: For creating smart contracts.
● IPFS (InterPlanetary File System): T o securely store documents.
Backend:
● Node.js: Server-side logic.
● Python: For data validation and processing.
Frontend:
● React.js: Interactive web applications.
● Bootstrap: For responsive design.
Database:
● MongoDB: For storing metadata.
● PostgreSQL: For relational data.
Scalability
Phase 1: Pilot Launch
● T arget a single country or region with a high gender gap in STEM.
● Partner with universities and NGOs to promote the program.
Phase 2: Regional Expansion
● Integrate with global education platforms (e.g., Coursera, edX).
● Establish corporate sponsorships with tech companies.
Phase 3: Global Scaling
● Multi-language support for international accessibility.
● AI Integration: Predict future needs based on applicant trends.
Potential Challenges
Challenge 1: T echnological Literacy
● Solution: Develop an easy-to-use mobile app with educational
materials on blockchain and STEM.
Challenge 2: Data Privacy
● Solution: Use zero-knowledge proofs to verify eligibility without
exposing sensitive information.
Challenge 3: Internet Accessibility
● Solution: Offer offline application support and integrate with
community centres.


Hemali Chotalia
23BHI10073
GDG
WTM
TASK2
_
_
Project: Sentiment Analysis of Product Reviews
Step 1: I downloaded a Twitter Sentiment Analysis dataset from Kaggle, which contains
tweets and their corresponding sentiments (Positive/Negative).
Step 2: Installed and imported the necessary libraries for the analysis
Step 3: Data Preprocessing
● Cleaned T ext Data:
Removed noise (punctuation, stopwords, etc.) and tokenized the text into useful
features.
● Handled Missing Values:
Ensured that both the feature matrix X and target labels y were free of NaN values
and aligned in size.
Step 4: Feature Extraction (TF-IDF)
● TF-IDF (T erm Frequency-Inverse Document Frequency):
Converts text data into numerical vectors. It reflects how important a word is in a
document relative to the entire dataset.
Step 5: Splitting the Data
● Train-T est Split:
○ Training Set (80%): Used to train the model.
○ T est Set (20%): Used to evaluate model performance.
Step 6: Model Training
● Logistic Regression:
Fitted the model using the training data (X_train and y_train).
Step 7: Predictions:
Used the test data (X_test) to predict sentiments.
Evaluation Metrics:
Calculated accuracy, precision, recall, and F1-score to assess performance.
