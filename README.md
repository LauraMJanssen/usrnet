# USRNet

USRNet = *Deep Unfolding Super Resolution Network* for IVUS Images

Based on the repository by [Kai Zhang](https://github.com/cszn/KAIR)

## Training
- by executing 'main_train_psnr.py'
- Code: 
	**python main_train_psnr.py --opt options/train_usrnet.json**
- add other arguments if required


## Execution
- upload USRNet.ipynb file to Google Colaboratory
- follow instructions
- execute elements in the order they are included


## File Structure
- **USRNet.ipynb**: Google Colaboratory execution file
- **main_train_psnr.py**: training functions 
- **models**: implementation of the USRNet model
- **options**: includes USRNet configuration file
- **data**: function to prepare the dataset
- **utils**: some additional functions
- **SRImages**: some example images generated with the USRNet model and LR input images
- **trainedModel**: fully trained model 


