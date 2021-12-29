I've done work to build a Computer vision model using fastai using pytorch. After training a successful model, the model can predict the tags for any images with a certain high probability. Barcode is ID, image column is name of image in the folder & all other are tags related to image for both different prints & colors.

Except Barcode & image all are tags label.

During inference, hard to judge the results just by True/False. We can have some images display same time during prediction.
