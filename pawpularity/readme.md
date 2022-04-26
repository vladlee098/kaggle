PetFinder.my - Pawpularity Contest
In this competition, you’ll analyze raw images and metadata to predict the “Pawpularity” of pet photos. You'll train and test your model on PetFinder.my's thousands of pet profiles. Winning versions will offer accurate recommendations that will improve animal welfare.

Photo Metadata
The train.csv and test.csv files contain metadata for photos in the training set and test set, respectively. Each pet photo is labeled with the value of 1 (Yes) or 0 (No) for each of the following features:

Focus - Pet stands out against uncluttered background, not too close / far.
Eyes - Both eyes are facing front or near-front, with at least 1 eye / pupil decently clear.
Face - Decently clear face, facing front or near-front.
Near - Single pet taking up significant portion of photo (roughly over 50% of photo width or height).
Action - Pet in the middle of an action (e.g., jumping).
Accessory - Accompanying physical or digital accessory / prop (i.e. toy, digital sticker), excluding collar and leash.
Group - More than 1 pet in the photo.
Collage - Digitally-retouched photo (i.e. with digital photo frame, combination of multiple photos).
Human - Human in the photo.
Occlusion - Specific undesirable objects blocking part of the pet (i.e. human, cage or fence). Note that not all blocking objects are considered occlusion.
Info - Custom-added text or labels (i.e. pet name, description).
Blur - Noticeably out of focus or noisy, especially for the pet’s eyes and face. For Blur entries, “Eyes” column is always set to 0.

https://www.kaggle.com/c/petfinder-pawpularity-score


LGBM, TabOnly, Optuna