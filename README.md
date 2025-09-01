## Data Cleaning
   - Missing values in numerical columns were filled with median.
   - Duplicates removed.
   - Outliers in numerical columns handled using IQR method.
   - Data types corrected for numerical columns by using to_numeric()
## EDA:
   -Checked distribution of each numeric feature by plotting histograms. Checked if they followed a normal distribution or whether they are skewed. It also helped     to identify outliers visually.
   -The histogram of fighter heights shows that the majority of UFC fighters are concentrated between 180-190 cm indicating this is the most common height range. 
   -The histogram of significant strike defence shows that most UFC fighters fall within the 50–60% range, suggesting that the typical fighter avoids about half       of incoming significant strikes. 
   -A small number of fighters exceed 80%, making them good defensive specialists, while very few fall below 40%, indicating poor defensive skill.
   -KDE plots for numeric columns helps to tell whether the data is normal(bell-shaped),skewed,uniform. The peak indicates the mode. weight_in_kg has multiple         peaks suggesting fighters cluster around standard weights(70kg,84 kg)
   -Height and reach show a strong positive correlation meaning taller fighters usually have longer reach.
   -The boxplot tells us that the median weight lies between 60-80kg. Since the upper whisker is longer, more fighters are on the heavier side.
   -Orthodox stance is most common among UFC fighters.
   -Travis Fulton has the most number of wins as seen from the barplot.
   -The regression plot shows a slight positive correlation between reach and number of wins. This suggests that fighters with a long reach have slight             competitive advantage.
   -The pairplot reveals that height and weight show a strong positive correlation. reach also tends to increase with height. 
## Conclusion:  
   - The cleaned dataset is ready for predictive modeling or deeper analysis, like performance prediction.
