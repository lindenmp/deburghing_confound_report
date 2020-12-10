# deburghing_confound_report

# Environment build

    conda create -n deburghing_confound_report python=3.7
    conda activate deburghing_confound_report

    # Essentials
    pip install jupyterlab ipython pandas numpy seaborn matplotlib nibabel nilearn ipywidgets tqdm
    pip install jupyter_contrib_nbextensions && jupyter contrib nbextension install

	# Statistics
	pip install scipy sklearn statsmodels confounds neuropredict

    cd /Users/lindenmp/Google-Drive-Penn/work/research_projects/deburghing_confound_report
    conda env export > environment.yml
	pip freeze > requirements.txt
