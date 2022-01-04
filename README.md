# biweekly-report-4-sgreenlund3
biweekly-report-4-sgreenlund3 created by GitHub Classroom

In this set of notebooks, I work to implement model interpretation. I use a dataset of CT images related to COVID to explore this, which are converted from DICOM to png in the data processing notebook. I first work to create a saliency map with a subset of the data. I then use the same subset to build out a gradCAM, using the same superimposition function from my saliency map to show the gradCAM. Finally, I rerun the gradCAM setup with the full dataset and discuss the results/work at the end of that notebook.

I don't focus too much on actually tuning the model, since I want to work more on getting the interpreation to work the way I want. As a result, we can see issues with my model in the full dataset version, which I discuss in the full dataset gradcam notebook. Namely, the validation/training is not split properly, so there are images in both that belong to the same patient. 

As I do manage to implement both saliency and gradCAM, I do consider these notebooks a success, despite not tuning the model or manually separating my validation and training data.
