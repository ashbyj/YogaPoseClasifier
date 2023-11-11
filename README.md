# Yoga Pose Identification
Data provided by A. Mohan Kumar by way of a benevolent [Kaggle](https://www.kaggle.com/datasets/amohankumar/yoga-pose-classification-dataset) upload.
## Problem statement
What are the key characteristics of a yoga pose that could be made ready for a motion tracking system to use within 1 year to identify poses in pre-recorded video or through a live feed?
## Context
Computer vision and analysis has been applied to many different move and sport problems so far.  Yoga is a natural step in that process.  Two of the most cited reasons for not going to a yoga studio are travel constraints and embarrassment in not knowing how to do the poses properly.  Removing the classroom and giving the new practitioner feedback and instruction in their home would answer both reasons.
## Criteria for success
This analysis will be a success if a model can be developed to identify yoga poses with at least 90% accuracy on novel examples.  
## Scope of solution space
This analysis will be scoped to placement and position of the human body in space in relation to the 9 poses that this dataset provides examples for.
## Constraints
The training data was collected from google image searches and contains pictures of poses only from the side angle.  The correctness of these poses has not been validated by any yoga body and any nuance in a pose only visible from the front or rear would be missed.
## Stakeholders
Stakeholders include new yoga practitioners, yoga trainers, yoga studio owners and those interested in designing instructional yoga content to be used in the home.
## Data source
The primary data source to be used in this analysis was provided for public use to Kaggle.  It was assembled through downloading some of the results of a Google Image Search for 9 different yoga poses.  This data could be supplemented by adding additional images for the current poses or additional poses.  Images taken at different angles would be valuable.
## Methodology
Analysis will begin by examining the images for any errors in classification.  It will then progress into exploring the shape and content of the images.  Additional images may also be sourced to expand the current set.  Various deep learning methods will then be applied to find the best combination of model type and hyperparameters.  As a final test, new images will be created or downloaded to test performance post analysis.  A formal report will be delivered on the findings.
## Deliverables
This analysis will yield 3 artifacts.
 1. document of the full analysis in the form of a digital notebook that includes reproducible code for review and examination.
 2. report of the project including a summary of the analysis, findings, history and avenues to continue the work.
 3. presentation of the report.
