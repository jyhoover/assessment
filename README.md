# Assessment

## SQL (folder)
- The 3 queries are in the jupyter notebook `SQL_queries.ipynb`, which was originally created on Google Colab. Here is the link if online reviewing is preferred. Anyone with this link has access to this file.
https://drive.google.com/file/d/1-iDO3RF_lkr-lYG-GW8Idyiqn4A8ZJVk/view?usp=sharing

## ML (folder)

- The detailed data analysis (with marks and comments on visualization, model choosing and result analysis) is in the jupyter notebook `ML_assignment.ipynb`, which was originally created on Google Colab. Here is the link for the best quality purposes. Anyone with this link has access to this file.
https://colab.research.google.com/drive/1ZzO2LIPaI5dpvSAoA9wQN-c1SycUc3Py?usp=sharing

- `slides.pdf` includes 2 slides explaining key insights and findings from the process that would be delivered to a business stakeholder.

### Models (folder)

- The trained chosen model is called `model_213_no_state_age.pickle`, which is described in Section 2.1.3 of the notebook

### Data (folder)

- The requested output is in `Scores.csv` with the header anon_person_id | target | prediction | probability. Notice that the `probability` here is the probability of the predicted class. It's always larger than 0.5. For example, if prediction is 0, the corresponding probability is 0.8 (class 0). not 0.2 (class 1); if another sample's prediction is 1, the the corresponding probability is 0.8 (class 1), not 0.2 (class 0).

- The score file (35 MB) is large. A Google Drive file is shared here too. https://drive.google.com/file/d/1-3g6mQpLwvWts9MMqUA_w4o8VNa5lsXX/view?usp=sharing
