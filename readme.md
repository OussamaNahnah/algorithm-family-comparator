# Algorithm Family Comparator

A standalone HTML tool for comparing algorithms across classification families.

Includes a difference matrix, pair comparisons, global similarity rankings,
and a family/group tree. No installation or build step required.

## Usage

Open the page with a classification data folder URL:

family_comparison_live.html?data=https://example.com/A3/global_classification_data
or family_comparison_live.html?data=https://oussamanahnah.github.io/RoAGt_drafts_A/A3/global_classification_data

The folder must contain:
- common_data.min.js with a family_titles list
- family_<id>.min.js files using the supported classification format

Available families are loaded automatically; missing files are skipped.
Large datasets use pagination and background calculations.

## Data independence

No execution data is bundled. The page loads the dataset supplied through
the data URL. It supports any execution using the same classification format.
