# oops-doc

How to build the OOPS documentation
-----------------------------------

**Run Doxygen**

> cd ${oops-src-directory}/Documents
> 
> doxygen ${oops-doc-directory}/Doxyfile.mf

**Move html into oops-doc repository**

> mkdir -p ${oops-doc-directory}/${oops-version}
> 
> mv ${oops-src-directory}/Documents/html ${oops-doc-directory}/${oops-version}

**Add index.html and shortcut.html in ${oops-doc-directory}/${oops-version}**

> cp ${oops-doc-directory}/cy49t0/index.html ${oops-doc-directory}/${oops-version}
>
> cp ${oops-doc-directory}/cy49t0/shortcut.html ${oops-doc-directory}/${oops-version}
>
> Fix URLs in shortcut.html
