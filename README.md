# Launch Jupyter notebook in appmode

[Appmode](https://github.com/oschuett/appmode) is useful for displaying Jupyter notebooks as web apps, with all the code hidden. But you can't use `appmode` within Jupyter Lab. Here's some code to create a button that launches the current notebook in `appmode`. It works in either Jupyter Lab or the classic notebook view. If `appmode` isn't available it does nothing.

To try it out [open this notebook in Jupyter Lab on Binder](https://mybinder.org/v2/gh/wragge/appmode-launcher/master?urlpath=%2Flab%2Ftree%2Flaunch_in_appmode.ipynb), then run the cell. Click on the button to switch to `appmode`.
