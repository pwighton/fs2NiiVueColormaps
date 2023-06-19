# fs2NiiVueColormaps

NiiVue comes with many built-in colormaps, which you can explore in this [live demo](https://niivue.github.io/niivue/features/colormaps.html). The NiiVue format is [described here](https://github.com/niivue/niivue/blob/main/docs/development-notes/colormaps.md). 

However, FreeSurfer uses a different format [for its Color Lookup Tables](https://surfer.nmr.mgh.harvard.edu/fswiki/LabelsClutsAnnotationFiles). This Python script converts files in the FreeSurfer format to NiiVue's format. The script will convert all the text files (`*.txt`) in the folder to JSON files. The included color tables are from [PyROI](https://github.com/mwaskom/PyROI/tree/master/data/Freesurfer) 

```bash
git clone https://github.com/niivue/fs2NiiVueColormaps
cd fs2NiiVueColormaps
python fs2niivue.py 
```

