# Custom Mask Detection Model (light)

## Content
This repo contains: 
- Two pre-trained models - one is custom trained by AIN for mask recognition,
other is ResNet SSD model for Face detection
- The original training script
- Link to original dataset (rar file ~300MB): [IPFS link](https://gateway.pinata.cloud/ipfs/QmapjkJto9GdGqTg3t7QyNUMiG24st2Er3RXksPyDr1hzj)
- Two scripts to detect mask on images and live camera stream
- Example images and results
- `requirements.txt` with dependancies 

## Requirements
`Python3`

## Install
```pip install -r requirements.txt```

## Usage
```python detect_mask_on_image.py -i <image_path>```

or

```python detect_mask_on_stream.py```

## Licence MIT
AIN LLC - https://ain.rs
