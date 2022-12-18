**Problem statement:**  <br>
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. <br>
A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

### <font color='cyan'> Sections in this notebook: <font>
I. Importing Skin Cancer Data 
    
    I.1. Importing all the important libraries
    I.2. Load using keras.preprocessing
    I.3. Visualize data

II. Create the model

    II.1. Normalize pixel values between (0,1)
    II.2. Building models
        II.2.1. One dropout layer after Dense layer
            II.2.1.1. First configuration
            II.2.1.2. Second configuration
        II.2.2. One dropout layer after each MaxPooling Layer
            II.2.2.1. First configuration
            II.2.2.2. Second configuration

III. Data Augmentation strategies
    
    III.1. Getting the class distribution
    III.2. First augmentation strategy
    III.3. Model Creation    
        III.3.1. First configuration without dropout
        III.3.2. First configuration with dropout
    III.4. Different augmentation strategy
        III.4.1 Perspective skewing
        III.4.2 Mirroring
        III.4.3 Shearing
        III.4.4 Random brightness
        III.4.5 Elastic distortions
    III.5. Playing around with the best combinations

IV. Conclusion
    