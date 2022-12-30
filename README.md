This is a quick analysis of data from the [SWAN study](https://www.swanstudy.org) (Study of Women's Health Across the Nation). The main motivation was to get a sense of whether FSH levels could be a reliable indicator of the menopause transition. Note that this is absolutely not a scientific study.

The data used includes the baseline study and visits 1 through 10. The notebook expects a `data/` folder, containing the following subfolders, each for a dataset:
- `baseline-1996-1997`
- `visit1-1997-1999`
- `visit2-1998-2000`
- `visit3-1999-2001`
- `visit4-2000-2002`
- `visit5-2001-2003`
- `visit6-2002-2004`
- `visit7-2003-2005`
- `visit8-2004-2006`
- `visit9-2005-2007`
- `visit10-2006-2008`

The Python environment has been setup using [Poetry](https://python-poetry.org) and can be reproduced by running `poetry install` from the root of the repository.