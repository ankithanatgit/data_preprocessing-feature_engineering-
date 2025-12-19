# Feature Engineering Documentation

## Engineered Features

1. avg_monthly_spend  
   - TotalCharges / tenure

2. tenure_group  
   - Categorized tenure into lifecycle groups

3. is_long_term_customer  
   - Binary indicator for customers > 24 months

4. charges_per_tenure  
   - MonthlyCharges normalized by tenure

5. high_value_customer  
   - Flag based on median MonthlyCharges

6. monthly_charge_ratio  
   - MonthlyCharges scaled by maximum value

7. senior_long_term  
   - Interaction between SeniorCitizen and tenure
