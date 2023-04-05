# Coursework submission guidance

This document contains generic information about the coursework (i.e. tutorial and project notebooks),
including guidance on submission.

## Jupyter Notebooks

Coursework will be provided and submitted as Jupyter Notebooks.

You do not need to download the tutorial notebooks to work on them; they will run in your web browser.
There is a link in Moodle which will take you to your own private copy of
the notebooks. When you **save** the notebooks, any changes you have made will
still be there the next time you click the link from any device.

The notebooks will also periodically autosave, though you should not rely on this!

## Validation

The coursework notebooks may already contain a number of code cells marked `# VALIDATION CELL` or `# Don't edit this cell`.
You do not need to, and should not, make any changes to these cells. Running one
of these cells will perform some simple checks on the format of your workOB
(for example, checking whether you have defined the variable a question asks for).
If a problem is detected an error will be produced giving you some feedback;
if there is no detected problem there will be no output.

If an error is produced, it will indicate which line in the validation cell failed;
it will often be a line including the word `assert`.
There may be a comment above this line indicating what is being tested.

For example, if you were asked to write a function called `reverse` which reverses
a list, there might be lines in the validation cell which look like this:

```
# reverse([1, 2, 3, "a"]) should be ["a", 3, 2, 1]
nbg_tc.assertEqual(reverse([1, 2, 3, "a"]), ["a", 3, 2, 1])
```

In this case, there is an "assertion" that the result of `reverse([1, 2, 3, "a"])`
should be equal to `["a", 3, 2, 1]`. If an error is produced from this line, you
should go back and work out why your code does not produce this correct answer.

If the validation cells pass, it is **not** a guarantee that your solution is correct.

You can run all of the validation cells by clicking the `Validate` button on the
menu bar, but be aware that the validation for questions you have not attempted yet will automatically fail.


## Submitting your notebook

To submit a piece of coursework, you need to download the notebook from the server and upload it via
the MySaint coursework submission tool.

You can download your file as a notebook via the `File` menu: `File>Download As>Notebook (.ipynb)`.
You will likely not be able to open the file on your own computer, but you can still upload it to MySaint.

## Notebooks must run from top to bottom

Since Jupyter Notebooks allow cells to be run out-of-order, it is **crucial** that
you check that your notebook works when run sequentially with a fresh Python kernel.
To check this, click `Kernel>Restart & Run All`,
and check that the output from your cells is what you expect. This is how the
marker will run your notebook.

Marks will be deducted if your cells need to be manually run in a particular order,
or multiple times, to produce the answer.

## Server issues

Please email Dan Lucas (dl21@) and Finn Smith (fls3@) if you encounter
any technical issues with JupyterHub.

## Accidentally modified or deleted cells

If you have accidentally deleted or modified a cell and you now cannot recover it,
follow these steps:

1. Click the JupyterHub logo in the top-left to view all of your files.
2. Click the box on the left of the folder corresponding to this course.
3. Click "Rename" and give the folder a new name (e.g. "old-MT3510-coursework").
4. Log out of the server and then log back in via the Moodle link. This will give you a fresh copy of *all* of the released coursework notebooks.
5. Copy your work across to the fresh notebook.
6. Double-check that you have copied everything correctly!
7. Continue working on the new copy of the coursework.

## Local Python installations

If you have your own installation of Python, we strongly recommend that you do not use it
to do your coursework. If you do, it is your responsibility to ensure that
your notebook still works on the server, as that is the environment that the markers will use.

## General guidance

This section contains some generic Python advice.

1. The exact and complete Python code required to solve each problem should be
  contained in the submitted file. Do not expect markers to follow instructions like
  "uncomment this to see the answer".
2. Written answers belong in text cells, not in comments (unless otherwise specified).
3. If you require a computation to justify an answer, then that computation must actually
  happen in the notebook! This is just the standard rule of "show your working".
4. The submitted files should be "self-contained", meaning that everything that is
  required to run the files are contained in the files. The only modules that should
  be `import`ed are those provided along with the coursework (if any) and, if necessary,
  standard Python modules.
5. If you are not sure whether a library function is permitted (e.g. if a function from `numpy` makes
  a question trivial), ask.
6. Beware of the difference between `print` and `return` in a function.
7. Do not confuse the strings `"True"` and `"False"` with the boolean values `True` and `False`.
8. Provide answers to an appropriate level of accuracy; leave exact values
  unrounded unless there is a good reason to do otherwise.
