# CS479-FinalProject
**MUST BE USING MATLAB R2020B**
Use: 
- VGGish
- Bag of Words
- Arbimon

To compare data through UMAP


To install VGGish run these commands seperately:
- downloadFolder = fullfile(tempdir,'VGGishDownload');
- loc = websave(downloadFolder,'https://ssd.mathworks.com/supportfiles/audio/vggish.zip');
- VGGishLocation = tempdir;
- unzip(loc,VGGishLocation)
- addpath(fullfile(VGGishLocation,'vggish'))
