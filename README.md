# pdiot-ml

## 

## Model illustration

```txt
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 lstm (LSTM)                 (None, 50, 128)           67584     
                                                                 
 dropout (Dropout)           (None, 50, 128)           0         
                                                                 
 batch_normalization (Batch  (None, 50, 128)           512       
 Normalization)                                                  
                                                                 
 lstm_1 (LSTM)               (None, 50, 128)           131584    
                                                                 
 dropout_1 (Dropout)         (None, 50, 128)           0         
                                                                 
 batch_normalization_1 (Bat  (None, 50, 128)           512       
 chNormalization)                                                
                                                                 
 lstm_2 (LSTM)               (None, 128)               131584    
                                                                 
 dropout_2 (Dropout)         (None, 128)               0         
                                                                 
 batch_normalization_2 (Bat  (None, 128)               512       
 chNormalization)                                                
                                                                 
 dense (Dense)               (None, 64)                8256      
                                                                 
 dropout_3 (Dropout)         (None, 64)                0         
                                                                 
 dense_1 (Dense)             (None, 11)                715       
                                                                 
=================================================================
Total params: 341259 (1.30 MB)
Trainable params: 340491 (1.30 MB)
Non-trainable params: 768 (3.00 KB)
_________________________________________________________________
```

![s01221411142023](https://image.discover304.top/s01221411142023.png)



<!-- ## Adding a Submodule
1. To add a submodule to your repository, navigate to your repository's root directory and use the following command:

   ```sh
   git submodule add <repository-url> <path-to-submodule>
   ```
   - `<repository-url>`: The URL of the submodule repository.
   - `<path-to-submodule>`: The path within your repository where the submodule should be placed.

   For example:
   ```sh
   git submodule add git@github.com:specknet/pdiot-data.git .
   ```

2. After adding the submodule, you'll see it listed in a `.gitmodules` file in your repository. You should add this file to your repository:

   ```sh
   git add .gitmodules
   git commit -m "Added submodule"
   ``` -->

## Clone repo

When you clone a repository that contains submodules, you need to initialize and update the submodules. You can do this with a single command:

```sh
git clone --recurse-submodules git@github.com:YangSierCode000/pdiot-ml.git
```
