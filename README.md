# Action Search: Spotting Targets in Videos and Its Application to Temporal Action Localization
This repository is intended to host the Human Searches dataset and code from our [Action Search paper](http://humamalwassel.com/publication/action-search/). It includes the Human Searches dataset, code to animate the search sequences, and code (+ raw data) to reproduce the paper results figures.

<img src="./animate-searches/example_output/example_output_animation.gif">

If you find any piece of code valuable for your research, please cite this work:
```
@inproceedings{alwassel_2018_actionsearch,
  title={Action Search: Spotting Targets in Videos and Its Application to Temporal Action Localization},
  author={Alwassel, Humam and Caba Heilbron, Fabian and Ghanem, Bernard},
  booktitle={The European Conference on Computer Vision (ECCV)},
  month={September}
  year={2018}
}
```

# How to run it?

Install conda, create the environment from the `environment.yml` file, and then activate the environment:
```
conda env create -f environment.yml
source activate action-search
```

Launch `jupyter`, navigate to the desired notebook, and run the code!
```
jupyter notebook
```

# Who is behind it?

| <img src="http://activity-net.org/challenges/2018/images/humam.jpg" width="135" height="135"> | <img src="http://activity-net.org/challenges/2018/images/fabian.png" width="135" height="135"> | <img src="http://activity-net.org/challenges/2018/images/bernard.jpg" width="135" height="135">  |
| :---: | :---: | :---: |
| Contributor | Contributor  | Advisor |
| [Humam Alwassel][web-humam] | [Fabian Caba][web-cabaf] | [Bernard Ghanem][web-bernard] |

# Do you want to contribute?

1. Check the open issues or open a new issue to start a discussion around your new idea or the bug you found
2. Fork the repository and make your changes
3. Send a pull request

[web-humam]: http://www.humamalwassel.com
[web-cabaf]: http://www.fabiancaba.com
[web-bernard]: http://www.bernardghanem.com/
