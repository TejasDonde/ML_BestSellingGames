**Project: Best-Selling Steam Games of All Time Dataset (Machine Learning)**

This dataset includes global sales data for best-selling video games, featuring attributes like game title, platform, genre, publisher, release year and sales by region.

Dataset Overview

●       Rows: 2381

●       Columns: 15

●       Column Description

○       game_name: Title of the game.

○       Reviews_like_rate: Percentage of positive reviews.

○       all_reviews_number: Total number of reviews.

○       release_date: Original release date.

○       developer: Name of the development studio.

○       user_defined_tags: Tags given by users.

○       supported_os: Platforms supported.

○       supported_languages: Supported languages.

○       price: Listed price in USD.

○       other_features: Included features.

○       age_restriction: Age category.
○       rating: Overall game rating.

○       difficulty: Subjective difficulty label.

○       length: Estimated playtime in hours.

○       estimated_downloads: Proxy for game success.

**Approach**
Steps:
        •	Step 1: Data understanding , exploration and Importing Data
        
        •	Step 2: Data cleaning (handling nulls and outliers)
        
        •	Step 3: Pre-processing 
        
        •	Step 4: Data preprocessing (scaling, defining X&Y, Train_Test Split)
        
        •	Step 5: Model training (Classification)
        
        •	Step 6: Cross Validation
        
        •	Step 7: Final model selection and optimization

 **Conclusion**

        **Gradient Boosting has the highest AUC-ROC (0.97) and strong F1-score.---> balanced performance.**
                                                                                                                
        **Random Forest has the highest accuracy and F1.---> offering great stability.**
                                                                
        **Logistic Regression gives the best precision .---> useful for interpretation.**
                                                                
