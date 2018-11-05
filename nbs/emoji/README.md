# Face emotions detection

## Setup
```bash
/usr/bin/virtualenv -p /usr/bin/python3.6 venv
source venv/bin/activate
pip install http://download.pytorch.org/whl/cpu/torch-0.4.1-cp36-cp36m-linux_x86_64.whl
pip install fastai
pip install jupyter ipython jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
jupyter nbextension enable collapsible_headings/main
jupyter nbextension enable move_selected_cells/main
jupyter nbextension enable execute_time/ExecuteTime
jupyter nbextension enable toc2/main
```
