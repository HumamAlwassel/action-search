# Human Searches Datasets
We collect two new datasets of Human Searches, where videos are annotated with the search steps a human follows to temporally spot/localize human actions. These datasets are stored in two different CSV files:

>- **`thumos14-human-searches.csv`:** It includes search sequences collected from the training videos of THUMOS14. To gather this dataset, we asked the humans to find an action's *starting time.*

>- **`ava-human-searches.csv`:** This dataset includes human searches from 139 training videos from the AVA dataset. In this case, we ask the users to spot *any frame* inside temporal bounds of a given action.

Each dataset contains the following fields or columns:

`search-id`: an integer that identifies each search sequence.

`step-id`: an integer that specifies the current step number within a search sequence.

`video-id`: a string that maps the search sequence with its corresponding video.

`time`: a float that contains the absolute time in the video observed at the current step.

`target-action`: a string indicating the target action the human searched for.


Please **note** that here we are providing the raw dataset. To reproduce our results, please follow the pre-processing steps defined in [our paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Humam_Alwassel_Action_Search_Spotting_ECCV_2018_paper.pdf).
