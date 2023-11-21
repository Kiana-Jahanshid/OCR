# EasyOCR (Optical character recognition)

detection + recognition 

# Description 
input_image ---> DETECTOR ---> predict bounding boxes ---> RECOGNIZER ---> recognized words 


in last project we used YOLO to detect the license plates .
AND now , we are going to recognize those license plate character .

**OCR** means recognize a text which has been detected before . 



# How to install 
Run this command to install used libraries :

pip install -r requirements.txt 

# How to run 

you just need to run `EasyOCR.ipynb` file .

# RESULTS


## 1-   Inference on a latin hand-writing text image

image :
<p float="center">
    <img src  = "assets/eng_handwriting.png" width=250 /> 
</p>
result :<br/>
['door', 'mind', 'pOOr', 'behind', 'Yloor_', 'child', 'becaWse', 'children', 'Yind', 'wild', 'kind', 'clinb']

# _____________________________________________________________________

## 2- Inference on a persian hand-writing text image
image :
<p float="center">
    <img src  = "assets/persian_handwriting.jpg" width=250 /> 
</p>
result : <br/>
['سمالند الرحمن', '~ نام حداور حان رحرد', 'کزبن برترا نذدشد درنلدرد', 'الرحم']

### _____________________________________________________________________
image :
<p float="center">
    <img src  = "assets/persian_hw.jpeg" width=250 /> 
</p>
result : <br/>
['های', 'هروسٰ بسته', 'اهورش دست', 'خط']

### ____________________________________________________________________

# Inference on a latin license plate image
image :
<p float="center">
    <img src  = "assets/LP_EN1.jpg" width=450 /> 
</p>
result : <br/>
['AH', '965 WM', 'AUTOFRANCI', 'E FIAT', 'cordialita -cortesia - assistenza']

### _____________________________________________________________________
image :
<p float="center">
    <img src  = "assets/LP_EN2.jpg" width=450 /> 
</p>
result :<br/>
['UA', 'BM 2065 XP', 'QERONE', 'WWW krone de']


# ______________________________________________
# Inference on a persian license plate image

image :
<p float="center">
    <img src  = "assets/IMG_20231120_161720.jpg" width=450 /> 
</p>
result :<br/>
['ایل ان', '٦٦ ٦٥٧ج', '`', '02/08/25_', '٥٥', '8300657-66', '٨٣']

### ___________________________________________________________

image :
<p float="center">
    <img src  = "assets/IMG_20231120_161805.jpg" width=450 /> 
</p>
result :<br/>
['٥٤٥٩٢٧٩٩', '٨']

### ___________________________________________________________

image :
<p float="center">
    <img src  = "assets/IMG_20231120_161838.jpg" width=450 /> 
</p>
result :<br/>
['اببدان', '٥٨', '٥٥ ٤٨٨٣ ٦٩']

### ___________________________________________________________

image :
<p float="center">
    <img src  = "assets/IMG_20231120_161959.jpg" width=450 /> 
</p>
result :<br/>
['ایید اث', '1./.', '١٠ ٢٦٢س٤٢', '٥', '4258262`10', '9/07/10']

### ___________________________________________________________


