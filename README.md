# oops-doc

cd ${oops-src-directory}/Documents
doxygen ${oops-doc-directory}/Doxyfile.mf
mkdir -p ${oops-doc-directory}/${oops-version}
mv ${oops-src-directory}/Documents/html ${oops-doc-directory}/${oops-version}
