# Foundation of Modelling and Simulation

Hands-on notebooks for **CSI 4124 / SYS 5110** at the University of Ottawa.

Every activity on this site is a Jupyter notebook. There are three ways to run one,
and which you should use depends on what you're doing.

## 1. Google Colab — use this in class

Each notebook page has a Colab link. It opens in a few seconds, runs on Google's
machines, and saves your work to your Google Drive. This is the path to use during
a live activity.

You need a Google account. uOttawa is a Microsoft shop, so this will often be a
personal Gmail rather than your uOttawa address — either works.

## 2. JupyterLite — no account needed

If you'd rather not sign in to anything, [open the notebooks in JupyterLite](https://www.gstonge.ca/csi4124-sys5110/lite/lab/index.html).
Python runs **inside your browser tab** — there is no server to log into and nothing
to go down.

Two things to know:

- The first load downloads a chunk of Python (tens of MB). It's cached afterwards.
- **Your work is saved in your browser, not in the cloud.** It survives closing the
  tab, but it's tied to that one browser on that one machine, and clearing your site
  data erases it. Fine for a one-hour activity; do not keep multi-week work here.

## 3. A local Python install — use this for graded work

Getting Python running on your own machine is part of what this course expects you to
be able to do. Do it in week 1, not the night before something is due.

```bash
git clone https://github.com/gstonge/csi4124-sys5110.git
cd csi4124-sys5110
python3 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
python3 -m pip install numpy matplotlib jupyterlab
jupyter lab
```

Then open any notebook under `notebooks/`.

---

*Notebooks on this site are shown with their outputs already filled in, so you can
read a page without running anything.*
